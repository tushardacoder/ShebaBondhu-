

# Product Requirements Document (PRD)
# ShebaBondhu – All-in-One Local Services Marketplace

**Working Brand:** ShebaBondhu (সেবাবন্ধু)  
**Tagline:** Your Neighborhood, Everything You Need(আপনার সব প্রয়োজন, এক ঠিকানায়)
**Product Type:** Hyperlocal Multi-Service Marketplace  
**Target Market:** Bangladesh  
**Initial Launch:** One selected local area, followed by expansion  
**Document Version:** 1.0

---

## 1. Product Overview


### 1.1 Introduction

ShebaBondhu is an all-in-one digital marketplace designed to connect local customers with service providers, landlords, tenants, transportation providers, educational professionals and businesses.

The platform will provide a centralized solution for everyday needs, including:


- House rentals and property management.
- Home repair and maintenance services.
- Packers and movers.
- Salon and beauty appointments.
- Private tuition and tutor discovery.
- neighborhood services such as finding (electricians, gas technicians , plumbers and other technicians).
- Customer feedback and provider ratings.

Instead of using different platforms for different services, users can access everything through one application.

### 1.2 Problem Statement

People in Bangladesh frequently face difficulties when searching for local services.

Examples:

1. Finding trustworthy rental properties and landlords.
2. Finding reliable electricians, gas technicians , plumbers and other technicians.
3. Negotiating service prices before hiring technicians.
4. Finding transportation and labor for house shifting.
5. Booking salon appointments without visiting physically.
6. Finding qualified tutors in nearby areas.
7. Identifying trustworthy service providers through genuine reviews.

ShebaBondhu aims to solve these problems through a centralized, location-based marketplace.

### 1.3 Product Vision

To become a trusted digital platform where people can find, compare, negotiate, book and review almost every essential local service.

---

## 2. Target Users

### 2.1 Customer

A person looking for local services, properties, transportation or educational support.

### 2.2 Service Provider


Professionals offering services such as:

- Electricians.
- Gas technicians.
- Plumbers.
- AC technicians.
- Mechanics.
- Packers and movers.
- Tutors.

7- Other local professionals(driver, and others)

### 2.3 Business Owner

Individuals or organizations managing:

- Rental properties.
- Salons.
- Transportation businesses.
- Local shops.
- Other service businesses.

### 2.4 Admin

Responsible for platform management, user verification, moderation, complaints, transactions and analytics.

A single user account may have multiple roles.

---

# 3. Functional Requirements and Modules

## Module 1: Authentication and User Management

Features:

- Registration using mobile number or email.
- OTP verification.
- Login and logout.
- Password reset.
- User profile management.
- Profile picture.
- Multiple user roles.
- Saved addresses.
- Account verification.
- Account suspension and reporting.

Users can switch between customer and provider activities without creating multiple accounts.

## Module 2: House Rental Marketplace

### Landlord Features

- Register as a landlord.
- Create rental property listings.
- Upload multiple property images.
- Add property descriptions.
- Specify monthly rent.
- Specify advance payment.
- Specify bedrooms, bathrooms and facilities.
- Select property location.
- Add availability date.
- Manage inquiries.
- Accept or reject rental requests.
- Mark properties as rented or available.

### Tenant Features

- Search properties by location.
- Filter by monthly budget.
- Filter by bedrooms and bathrooms.
- View property details and images.
- Contact landlords.
- Request property visits.
- Submit rental inquiries.
- Save favorite properties.
- Review verified landlords.

### Additional Features

- Verified property badges.
- Fake listing reporting.
- Landlord reviews.
- Property availability management.
- Rental inquiry management.

## Module 3: Home Services and Technician Marketplace

### Service Categories

- Electrical services.
- Gas line services.
- Plumbing.
- AC repair.
- Refrigerator repair.
- TV repair.
- Carpentry.
- Painting.
- Cleaning.
- General home maintenance.


### Provider Features

- Create technician/service provider profiles.
- Select service categories.
- Specify service areas.
- Add experience and qualifications.
- Set availability.
- Define initial service charges.
- Receive customer requests.
- Negotiate prices.
- Accept or reject bookings.
- Manage job status.
- View customer reviews.

### Customer Features

- Find technicians by location.
- Search by service category.
- View provider profiles.
- Compare prices and ratings.
- Submit service requests.
- Upload problem descriptions and photographs.
- Negotiate prices.
- Confirm bookings.
- Review completed services.

### Negotiation Workflow

1. Customer submits a service request.
2. Provider receives a notification.
3. Provider proposes a price.
4. Customer can accept, reject or counter-offer.
5. Provider can accept or counter again.
6. Both parties agree on a final price.
7. Booking becomes confirmed.

The final agreed price must be stored in the booking record.

## Module 4: Home Shifting and Packers & Movers

This module connects people who want to move their belongings from one house or location to another.

### Service Categories

- Apartment shifting.
- Office shifting.
- Furniture transportation.
- Pickup and covered van rental.
- Truck rental.
- Packing services.
- Unpacking services.
- Loading and unloading.
- Furniture dismantling and installation.

### Moving Service Provider Features

- Register as a moving company or individual provider.
- Add available vehicles.
- Specify vehicle capacity.
- Add transportation charges.
- Define operating areas.
- Register available laborers.
- Set availability.
- Receive moving requests.
- Submit quotations.
- Negotiate transportation and labor charges.
- Manage confirmed bookings.
- Update moving status.

### Customer Features

- Select pickup address.
- Select destination address.
- Select moving date and time.
- Specify property type.
- Specify number of rooms.
- Add furniture and item details.
- Upload pictures of belongings.
- Select vehicle type.
- Select packing and labor requirements.
- Receive quotations from providers.
- Negotiate prices.
- Confirm a moving service.
- Review the moving company.

### Moving Booking Workflow

1. Customer creates a moving request.
2. Customer provides pickup and destination locations.
3. Customer specifies furniture and transportation requirements.
4. Nearby providers receive the request.
5. Providers submit quotations.
6. Customer compares quotations.
7. Customer negotiates with selected providers.
8. Customer accepts a final quotation.
9. Provider confirms the booking.
10. Moving status is updated throughout the process.
11. Customer confirms delivery.
12. Customer submits feedback.

### Moving Status

- Request Submitted.
- Quotation Received.
- Negotiating.
- Booking Confirmed.
- Packing Started.
- Loading Started.
- In Transit.
- Unloading Started.
- Delivered.
- Completed.
- Cancelled.

## Module 5: Salon and Appointment Booking

### Salon Owner Features

- Register salon.
- Add salon information and photographs.
- Add services and prices.
- Register employees.
- Set working hours.
- Configure appointment durations.
- Manage available time slots.
- Accept or reject appointments.
- Manage cancellations.
- View booking history.

### Customer Features

- Search nearby salons.
- View salon ratings.
- View available services.
- Compare prices.
- Select salon staff.
- Select date and time.
- Book appointments.
- Cancel or reschedule.
- Receive booking reminders.
- Submit reviews.

### Scheduling Rules

- Prevent double booking.
- Consider service duration.
- Consider employee availability.
- Support configurable breaks.
- Allow booking cancellation according to business policies.

## Module 6: Tuition and Tutor Marketplace

### Tutor Features

- Create tutor profiles.
- Add educational qualifications.
- Add teaching experience.
- Select subjects.
- Select classes and education levels.
- Set expected monthly salary.
- Select teaching locations.
- Offer online or offline tuition.
- Receive tuition requests.
- Negotiate monthly fees.

### Student and Guardian Features

- Search tutors.
- Filter by class and subject.
- Filter by location.
- Filter by budget.
- View qualifications.
- View reviews.
- Post tuition requirements.
- Receive tutor applications.
- Negotiate monthly fees.
- Confirm tuition arrangements.

## Module 7: Reviews and Feedback

A centralized review system will serve every marketplace module.

Features:

- Five-star ratings.
- Written reviews.
- Review photographs where relevant.
- Verified booking reviews.
- Provider responses.
- Complaint reporting.
- Review moderation.
- Fraudulent review detection.

Users should only receive a verified-review label after a qualifying completed transaction or verified rental interaction.

## Module 8: Local Shops and Additional Services

The platform should support future expansion into:

- Grocery stores.
- Local product shops.
- Home cleaning.
- Vehicle repair.
- Photography.
- Event management.
- Catering.
- Gardening.
- Pest control.

The system should support adding new categories without rebuilding the core application.

---

# 4. Shared Platform Features

All modules should use shared services.

### 4.1 Location Management

- Country.
- Division.
- District.
- Upazila.
- Area.
- Neighborhood.
- Custom service zones.
- Pickup and destination locations.

Providers should be discoverable according to their service coverage.

### 4.2 Messaging and Negotiation

- Customer-provider chat.
- Text messaging.
- Image sharing.
- Price proposals.
- Counter-offers.
- Negotiation history.
- Booking-related communication.

### 4.3 Notification System

- Booking requests.
- Booking confirmation.
- New quotations.
- Negotiation updates.
- Appointment reminders.
- Cancellation alerts.
- Payment updates.
- Review notifications.

Support in-app and SMS notifications, with push notifications in future mobile applications.

### 4.4 Favorites and Saved Items

Users can save:

- Properties.
- Technicians.
- Salons.
- Tutors.
- Moving companies.
- Other service providers.

### 4.5 Payment Management

Future payment integration:

- Cash on delivery/service completion.
- bKash.
- Nagad.
- Rocket.
- Supported payment gateways.

Payment handling must distinguish booking amounts, advance payments, final payments, refunds and platform commissions.

---

# 5. Admin Panel

The admin panel is responsible for managing the entire ecosystem.

### Dashboard

- Total users.
- Total providers.
- Total property listings.
- Total service bookings.
- Total moving requests.
- Total salon appointments.
- Total tuition requests.
- Revenue and commissions.
- Pending verification requests.
- Complaints and disputes.

### User Management

- View users.
- Manage roles.
- Verify providers.
- Suspend accounts.
- Review reported accounts.

### Marketplace Management

- Manage categories.
- Moderate property listings.
- Manage service providers.
- Manage salon listings.
- Manage tutor profiles.
- Manage moving companies.

### Booking Management

- View all bookings.
- Monitor booking status.
- Handle cancellation requests.
- Manage disputes.
- Review transaction history.

### Review Management

- Moderate reviews.
- Investigate complaints.
- Remove policy-violating content.

### Platform Configuration

- Manage service categories.
- Configure commissions.
- Manage subscription plans.
- Configure notification templates.
- Manage promotional banners.

---

# 6. Business Model and Monetization

The platform can generate revenue through multiple channels.

1. **Booking Commission:** Charge a percentage of eligible completed service bookings.
2. **Provider Subscription:** Monthly or yearly subscriptions for professionals and businesses.
3. **Featured Listings:** Paid promotion for rental properties and providers.
4. **Advertisement:** Local business advertising.
5. **Premium Business Profiles:** Additional visibility and management features.
6. **Moving Service Commission:** Commission on completed transportation and shifting bookings.

The platform should clearly disclose all charges before confirmation.

---

# 7. Non-Functional Requirements

### Performance

- Fast search and filtering.
- Pagination for large listings.
- Optimized image storage.
- Efficient database queries.

### Security

- Secure authentication.
- Role-based authorization.
- Input validation.
- Protection against common web vulnerabilities.
- Secure payment integration.
- Rate limiting.
- Audit logs for important actions.

### Scalability

- Modular application architecture.
- Reusable shared services.
- Extensible service categories.
- Database indexing.
- Background processing.

### Usability

- Responsive design.
- Bangla and English support.
- Simple navigation.
- Mobile-first interface.
- Accessible forms.

### Reliability

- Transactional booking confirmation.
- No duplicate salon appointments.
- Controlled booking state transitions.
- Reliable notification processing.
- Backup and recovery strategy.

---

# 8. Recommended Technology Stack

### Backend

- C#
- ASP.NET Core Web API
- Entity Framework Core
- SQL Server
- ASP.NET Core Identity
- JWT Authentication
- SignalR
- Hangfire

### Frontend

- React.js or Angular
- TypeScript
- Bootstrap or Tailwind CSS

### Infrastructure

- Docker
- Cloud hosting
- Object storage for images
- Redis for caching when needed
- Google Maps or OpenStreetMap
- SMS and email integrations

### Architecture

Use a Modular Monolith with Clean Architecture initially.

Suggested layers:

- Domain
- Application
- Infrastructure
- Web API

Each business module should maintain clear boundaries and its own business rules.

---

# 9. Suggested Development Phases

### Phase 1: Platform Foundation

- Authentication.
- User profiles.
- Multiple roles.
- Location management.
- Admin dashboard.
- Categories and provider verification.

### Phase 2: Core Marketplace

- House rentals.
- Technician marketplace.
- Price negotiation.
- Reviews and feedback.

### Phase 3: Transportation Marketplace

- House shifting.
- Vehicle listings.
- Moving quotations.
- Labor management.
- Moving status tracking.

### Phase 4: Appointment and Education

- Salon registration.
- Staff scheduling.
- Appointment booking.
- Tutor registration.
- Tuition requirements.

### Phase 5: Shared Features

- Real-time chat.
- Notifications.
- Favorites.
- Complaint management.

### Phase 6: Business and Expansion

- Payment gateways.
- Provider subscriptions.
- Booking commissions.
- Advanced analytics.
- Mobile application.

---

# 10. MVP Scope

The first release should prioritize the following:

1. Authentication and user profiles.
2. Location-based property listings.
3. Technician discovery.
4. Technician price negotiation.
5. House shifting requests and quotations.
6. Centralized ratings and feedback.
7. Admin dashboard.

Salon and tuition modules can follow once the core marketplace is operational.

---

# 11. Success Metrics

Measure product success through:

- Number of registered customers.
- Number of verified providers.
- Active property listings.
- Successful rental connections.
- Completed technician bookings.
- Completed house shifting bookings.
- Salon appointments.
- Successful tutor connections.
- Booking conversion rate.
- Customer satisfaction ratings.
- Repeat customers.
- Provider retention.

---

# 12. Final Product Vision

ShebaBondhu will be a unified local marketplace where users can:

- Find a house to rent.
- Find tenants for their properties.
- Hire electricians, gas technicians and plumbers.
- Move furniture and belongings between houses.
- Book pickup vans, trucks and moving labor.
- Book salons and beauty appointments.
- Find private tutors.
- Discover other neighborhood services.
- Review and rate every eligible experience.

**One account. One platform. All local services.**


The long-term objective is to establish ShebaBondhu as a trusted neighborhood services ecosystem across Bangladesh.