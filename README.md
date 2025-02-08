# Movie Booking Website Physical Model Design
This document provides a brief overview of the Physical Model Design for an Online Movie Ticket Booking System. It outlines the key database entities and their relationships to manage movies, venues, users, bookings, payments, and seating arrangements.

Key Entities and Relationships

Movie: Stores movie details such as title, genre, release date, and director.

Venues & Screens: A venue has multiple screens; each screen has a unique number and seating capacity.

Timings & Events: Defines the show timings and scheduled events for movies.

Bookings: Users can make multiple bookings, each linked to a venue, movie, and time slot.

Seats & Selection: Tracks available seats and chosen seats for each booking.

Users & Admin: Registered users can book tickets, while an admin manages the platform.

Payments & Invoices: Payments are linked to bookings, with invoices generated for each transaction.

Bank Details: Stores user payment details for transactions.

![image](https://github.com/user-attachments/assets/71ef260c-698f-4e0c-99a3-b8abea80c9d8)
