# IoT Community Ecosystems Repository

This repository serves as a comprehensive data store for the IoT Community ecosystems directory, accessible at [iotCommunity.space/ecosystems](https://iotCommunity.space/ecosystems). It maintains structured information about various IoT components including:

- Network Servers
- IoT Gateways
- IoT Connectivity Solutions
- IoT Platforms
- Related datastores and companion services

## Data Structure

The repository uses JSON format to store ecosystem information. Each entry contains detailed specifications about IoT solutions. Here's an example of the data structure:

```json
{
  "SolutionName": {
    "Overview": "Brief description of the solution",
    "BusinessFeatures": [
      "Feature 1",
      "Feature 2",
      "Feature 3"
    ],
    "SensorsInTheBox": ["Compatible sensors"],
    "NetworkServers": ["Supported servers"],
    "Integrations": ["Compatible platforms"],
    "MobileApp": "Mobile application availability",
    "Editions": ["Available editions"],
    "Link": "Product URL",
    "Type": "Solution category",
    "AddedDate": "YYYY-MM-DD"
  }
}
```

## Current Solutions

The repository currently includes detailed information about various solutions, including:

1. ChirpStack
   - An open-source LoRaWAN Network Server
   - Developed by Broccar
   - Focused on providing economical solutions with complete network control

2. The Things Network (TTN)
   - Community-driven LoRaWAN Network Server
   - Offers global coverage through shared infrastructure
   - Ideal for community projects and non-commercial applications

## Contributing

We welcome contributions to expand and maintain this ecosystem directory. When adding new solutions, please ensure:

1. The data follows the established JSON structure
2. All required fields are completed
3. Information is accurate and up-to-date
4. The `AddedDate` field reflects the date of addition

## Usage

This data repository can be used to:
- Research IoT ecosystem solutions
- Compare different platforms and services
- Make informed decisions about IoT infrastructure
- Integrate with iotCommunity.space services

## Links

- Main Project: [iotCommunity.space/ecosystems](https://iotCommunity.space/ecosystems)
- About Page: [Project Information](https://iotCommunity.space/about)

## License

Please refer to the repository's license file for usage terms and conditions.
