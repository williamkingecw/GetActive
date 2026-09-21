# GetActive

GetActive is a lightweight, offline Active Directory structure simulator built to help administrators and engineers plan AD environments before making changes in production.

The idea is simple. Sometimes you need to work through an OU structure, move objects around, test layouts, or show someone what a proposed design will look like without touching a live domain.

GetActive gives you a basic ADUC-style environment that runs locally in a browser and does not require installation.

## What GetActive Does

GetActive allows you to build and manage a basic Active Directory structure using common AD objects.

Current functionality includes:

* Create Organizational Units
* Create Users
* Create Computers
* Create Groups
* Rename objects
* Edit object properties
* Move objects between OUs
* Delete objects
* Right-click object management
* F2 rename support
* General and Object property views
* Save and load environments

The goal is not to recreate every feature of Active Directory Users and Computers.

GetActive is meant to be a planning and visualization tool.

## Why I Built It

I spend a lot of time working with Active Directory environments, including cleanup, restructuring, migrations, and long-term planning.

While working through an AD restructure, I wanted a simple way to build an OU structure and manipulate objects without making production changes or standing up another lab environment.

Most of what I needed was visual.

Create an OU. Move a server. Rename something. Test a different structure. Show another engineer what the proposed environment would look like.

That became GetActive.

## How It Works

GetActive is a standalone HTML file.

There is no installer and no backend server required.

Download:

`GetActiveRC.html`

Open it in a modern web browser.

Everything runs locally on the workstation.

## Saving Your Work

GetActive supports saving and loading environments using its own project file format.

This allows you to build a structure, save it, and continue working on it later.

You can also share a proposed structure with another engineer without giving them access to the actual Active Directory environment.

## What GetActive Does Not Do

GetActive does not connect to Active Directory.

It does not:

* Query a domain controller
* Modify Active Directory
* Authenticate against AD
* Execute PowerShell
* Require domain credentials
* Send your environment anywhere

It is a standalone simulation and planning tool.

## Security and Privacy

GetActive runs locally in your browser.

It was intentionally designed as an offline tool so AD planning does not require uploading directory information to an external service.

Avoid placing passwords, credentials, or other sensitive information inside project files.

## Current Release

Current public build:

**GetActive Release Candidate**

File:

`GetActiveRC.html`

This release candidate includes the core functionality I originally wanted from the project and is being made available for testing and feedback before a final v1.0 release.

## Who It Is For

GetActive may be useful for:

* Active Directory administrators
* Systems administrators
* Infrastructure engineers
* Network engineers
* MSP engineers
* Consultants
* Homelab users
* Students learning Active Directory

## Project Scope

I want to keep GetActive relatively simple.

There are full lab environments, directory management products, and enterprise tools available already.

GetActive is not trying to replace those.

The goal is to provide a quick way to sketch an Active Directory environment, make changes, and work through a design before touching production.

## Feedback

If you run into an issue or have an idea that would make GetActive more useful, feel free to open an Issue on GitHub.

Feedback from people who actively manage Active Directory environments is especially useful.

## License

License information will be added as the project moves from Release Candidate to the final public release.

GetActive is proprietary software. Use is permitted under the terms provided in the LICENSE file. Modification and redistribution are not permitted without written permission.

## Screenshots

### Main Interface

![GetActive Main Interface](screenshots/getactive-main.jpg)

### Populated AD Structure

![GetActive Populated Structure](screenshots/getactive-populated.jpg)

### Object Properties

![GetActive Object Properties](screenshots/getactive-properties.jpg)


