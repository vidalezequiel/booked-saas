# Booked SaaS

Multi-tenant booking platform designed for businesses to manage appointments, clients and availability in a simple and scalable way.

## Overview

Booked is a SaaS platform that allows businesses to create their own booking system using a unique slug.

It solves the problem of fragmented scheduling tools by centralizing appointments, availability and customer management in a single system.

Currently used by 35+ clients within the first month of launch.

## Features

- Multi-tenant architecture based on slug
- Appointment scheduling system
- Client management
- Availability and time slot configuration
- REST API backend
- Web-based interface

## Tech Stack

- PHP (PDO)
- JavaScript
- MySQL
- REST APIs

## Architecture

- Central router (`index.php` + `.htaccess`)
- Modular structure:
  - `/pages`
  - `/includes`
  - `/functions`
- Per-page assets (CSS + JS)
- API endpoints returning JSON

## Status

Production – actively used by 35+ clients within the first month of launch, solving real-world scheduling and client management needs.

## Screenshots

![Booked Dashboard](./booked/booked1.png)
![Booking Flow](./booked/booked2.png)
![Calendar View](./booked/booked3.png)

## Website

👉 https://booked.blackshark.com.ar
