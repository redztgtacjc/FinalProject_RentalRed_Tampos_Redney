# Rental Property Management System

## What is this?
This is a desktop application built to help landlords and property managers easily keep track of their rental business. Instead of using messy spreadsheets, this system provides a clean, dark-themed user interface to manage tenant profiles, rental units, lease contracts, and payment collections all in one place.

## Key Features
* **Renter Management:** Create and store renter accounts with their contact information and secure login credentials.
* **Unit Tracking:** Add new rental units to the system, specifying the unit number, unit type (e.g., Studio, 1BR), and monthly rent price.
* **Lease Contracts:** Easily link a renter to a specific unit. The system tracks the start and end dates of the lease and prevents double-booking an already occupied unit.
* **Payment Portal:** A dedicated screen where renters can log in, see their balance, and submit rent payments using methods like GCash.

## Built With
* **Language:** Java
* **User Interface:** Java Swing (built with NetBeans GUI Builder)
* **Database:** SQL (connected via JDBC to store all renters, units, and leases securely)

## How It Works (The User Flow)
1. The landlord registers new **Rental Units** into the system.
2. The landlord creates **Renter Accounts** for new tenants.
3. In the **Lease Contracts** menu, the landlord selects a renter and a unit from dropdown menus, sets the dates, and issues the lease. 
4. The tenant can then use the **Renter Payment** screen to log in and pay their rent.
