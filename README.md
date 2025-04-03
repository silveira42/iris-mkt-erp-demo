# IRIS Market and ERP Demo

This repository contains a demo project for an integrated ERP and marketplace system, showcasing the capabilities of the IRIS platform as an integrator. The IRIS platform is designed to seamlessly connect various components of an enterprise resource planning (ERP) system with a marketplace, providing a unified solution for managing business operations and online sales.

## Project Structure

The project is divided into several submodules, each representing a different part of the system:

- **erp-backend**: Backend services for the ERP system, handling business logic, data management, and integration with other services.
- **erp-frontend**: Frontend application for the ERP system, providing a user interface for managing business operations.
- **mkt-frontend**: Frontend application for the marketplace, allowing customers to browse and purchase products.
- **mkt-frontend-angular**: Angular-based frontend application for the marketplace, offering an alternative user interface for customers.
- **iris**: Core services and utilities that facilitate communication and integration between the ERP and marketplace components.

## Getting Started

### Prerequisites

- Docker
- Node.js
- npm

### Installation

### Running the Project

#### Development

To start the development environment, use Docker Compose:

```sh
docker compose -f docker-compose.dev.yml up --build
