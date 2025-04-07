# SmartConnect API Faker

A JSON Server-based API faker for SmartConnect application.

## Description

This repository contains a JSON Server setup that provides fake API endpoints for the SmartConnect application. It includes mock data for:

- User authentication
- Monitoring devices and locations
- Product management
- Order management
- Categories

## Setup

1. Install dependencies:

```bash
npm install -g json-server
```

2. Start the server:

```bash
json-server --watch db.json
```

## Available Endpoints

- `/users` - User authentication data
- `/tokens` - Authentication tokens
- `/monitoringList` - Device monitoring hierarchy
- `/products` - Product catalog
- `/orders` - Order information
- `/categories` - Product categories

## Data Structure

The mock data is stored in `db.json` and follows a hierarchical structure for monitoring devices and locations.
