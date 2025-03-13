# GetLocation

A lightweight web application for capturing geographic coordinates and creating geofence boundaries. Perfect for implementing location-based attendance systems, geofencing applications, and other location-aware services.

Live Demo: [GetLocation App](https://get-location-eta.vercel.app/)

## Features

- 📍 Capture precise geographic coordinates
- 🎯 Set up to 4 boundary points for geofencing
- 🎮 Simple and intuitive user interface
- 📋 Easy coordinate copying and export
- ⚡ High-accuracy mode for GPS precision
- 📱 Mobile-friendly design

## Use Cases

- Attendance Systems
- Geofencing Applications
- Location Verification
- Area Boundary Definition
- Geographic Data Collection

## Getting Started

### Prerequisites

- Modern web browser with geolocation support
- Location services enabled on your device

### Installation

1. Clone the repository:
```bash
git clone https://github.com/sim-codes/GetLocation.git
```

2. Navigate to the project directory:
```bash
cd GetLocation
```

3. Open `index.html` in your web browser or serve it using a local development server.

### Usage

1. **Enable Location Services**
   - Ensure your device's location services are enabled
   - Grant location permissions to the website when prompted

2. **Capturing Points**
   - Click "Capture Current Location" to record a point
   - The active point is highlighted in green
   - Alternatively, click on a specific point box to select it before capturing
   - Repeat until all required points are captured

3. **Managing Points**
   - Copy individual points using the "Copy" button
   - Reset all points using the "Reset Points" button
   - Name your location using the text field in the export section
   - Copy all points to clipboard using the "Copy Points to Clipboard" button

4. **High Accuracy Mode**
   - Toggle "High Accuracy" for more precise GPS coordinates
   - Recommended for applications requiring precise boundaries

## Data Format

Exported data follows this structure:
```json
{
  "name": "My Location Name",
  "topLeftLat": 12.34567890,
  "topLeftLon": 98.76543210,
  "topRightLat": 12.34567891,
  "topRightLon": 98.76543211,
  "bottomLeftLat": 12.34567892,
  "bottomLeftLon": 98.76543212,
  "bottomRightLat": 12.34567893,
  "bottomRightLon": 98.76543213
}
```

## Technical Details

- Built with vanilla JavaScript
- Uses the Geolocation API
- No external dependencies
- Mobile-responsive design
- Cross-browser compatible

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with ❤️ by [sim-codes](https://github.com/sim-codes)
- Deployed on [Vercel](https://vercel.com)

## Contact

For issues, feature requests, or contributions, please visit:
[GitHub Repository](https://github.com/sim-codes/GetLocation)
- Deployed on [Vercel](https://vercel.com)
