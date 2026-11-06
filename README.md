# MatLink

**Public Transport Navigation and Matatu Route Discovery Platform**

## Overview

MatLink is a public transport navigation platform designed to help passengers navigate towns using matatus.

It helps users discover how to get from their current location to a destination using public transport, even when they are unfamiliar with the town or its matatu routes.

## Problem Statement

Navigating towns using matatus can be confusing, especially for newcomers and passengers unfamiliar with particular routes.

Passengers often struggle to identify the correct boarding stages, determine which matatus to take, estimate fares, navigate transfers, and know where to alight.

MatLink aims to simplify this experience through accessible, step-by-step public transport navigation.

## Core Features

- **Location Detection:** Identify the user's current location using GPS or allow manual location selection.
- **Destination Search:** Search for destinations by name or select a location on the map.
- **Stage Discovery:** Identify nearby matatu stages and the correct boarding stage.
- **Route Planning:** Discover suitable matatu routes, including journeys requiring transfers.
- **Fare Estimation:** View estimated fares for individual journey segments and the entire trip.
- **Journey Navigation:** Receive walking directions to stages and guidance throughout the journey.
- **Alighting Guidance:** Know where to alight when approaching the destination.
- **Journey Information:** View estimated walking time and travel time.
- **Notifications:** Receive relevant journey alerts, including boarding, transfers, and alighting.

## Target Users

- Regular matatu passengers
- People unfamiliar with a town
- Students
- Visitors and tourists
- Daily commuters
- Occasional public transport users

## Technology Stack

The proposed technology stack includes:

- **Mobile Application:** Flutter
- **Backend:** Go
- **Database:** PostgreSQL with PostGIS
- **API:** REST
- **Maps and Location:** Mapping and geolocation services
- **Containerization:** Docker

Technology choices will be finalized during the architecture phase.

## Project Structure

```text
matlink/
├── mobile/
├── backend/
├── database/
├── docs/
├── README.md
└── .gitignore
```

## Documentation

Detailed project documentation is maintained in the `docs/` directory.

- [Requirements](docs/requirements.docs)
- [System Architecture](docs/architecture.docs)
- [Database Design](docs/database-design.docs)
- [API Specification](docs/api-specification.docs)
- [User Flows](docs/user-flows.docs)
- [UI/UX Design](docs/ui-ux-design.docs)
- [Development Roadmap](docs/development-roadmap.docs)

## Project Status

Currently in the planning and requirements documentation phase.

## Vision

To make navigating towns using public transport simpler, clearer, and more accessible.