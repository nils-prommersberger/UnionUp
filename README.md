# UnionUp

**A comprehensive management platform for unions, clubs, and community organizations.**

UnionUp is a cross-platform application (iOS, Android, Web) designed to help community organizations manage their finances, inventory, members, roles, and events in one centralized place.

Each member has their own secure login and personal wallet within the organization, making it easy to track individual balances, purchases, and contributions.

---

## Features

### Financial Management
- **Personal Member Wallets**: Every member automatically gets their own wallet to track their balance (prepaid credits, debts, deposits)
- **Organization Wallets**: Separate wallets for different purposes (e.g., "Bar Revenue", "Event Fund", "Membership Fees")
- **Asset Wallets**: Track the value of equipment and inventory
- **Transaction Tracking**: Full double-entry bookkeeping with split transaction support
- **Transaction History**: Complete audit trail with configurable reversal timeframes

### Inventory & Stock Management
- **Consumables**: Track products with selling prices, wholesale costs, and images
- **Stock Operations**: Intake, outtake, and inventory audits
- **Threshold Alerts**: Automatic notifications when stock runs low
- **Analytics**: Revenue, expenses, and leakage tracking

### Member Management
- **User Profiles**: Comprehensive member information including contact details
- **Authentication**: Secure login with token-based authentication
- **Multi-Union Support**: Users can belong to multiple organizations

### Role-Based Access Control
- **Predefined Roles**: Admin, Treasurer, Stock Manager
- **Custom Roles**: Create organization-specific roles
- **Fine-Grained Permissions**: Control access to users, finances, inventory, and events

### Event Management
- **Event Scheduling**: Create events with start/end times
- **Role-Based Invitations**: Invite members by their roles
- **Attendance Tracking**: Monitor who's attending

### Notifications
- **Real-Time Updates**: Stay informed about organization activities
- **Customizable Settings**: Control which notifications you receive

---

## Tech Stack

| Component | Technology |
|-----------|------------|
| Mobile App | .NET MAUI (iOS & Android) |
| Web App | Blazor WebAssembly |
| API Server | ASP.NET Core |
| Database | PostgreSQL |
| ORM | Entity Framework Core |

---

## Project Structure

```
UnionUp/
├── App.Mobile/     # MAUI mobile application (iOS/Android)
├── App.Web/        # Blazor WebAssembly web application
├── App.Data/       # Shared data layer and services
├── Api/            # Shared API models and clients
├── Server/         # ASP.NET Core API server
└── Tests/          # Unit and integration tests
```

---

## Reporting Issues

We welcome bug reports and feature requests! When creating an issue, please follow these guidelines:

### Bug Reports

Please include:

1. **Description**: A clear and concise description of the bug
2. **Platform**: iOS / Android / Web (include OS version if relevant)
3. **Steps to Reproduce**:
   - Step 1
   - Step 2
   - ...
4. **Expected Behavior**: What you expected to happen
5. **Actual Behavior**: What actually happened
6. **Screenshots/Videos**: If applicable, add visual evidence
7. **Additional Context**: Any other relevant information``

### Feature Requests

Please include:

1. **Problem Statement**: What problem does this feature solve?
2. **Proposed Solution**: How would you like it to work?
3. **Alternatives Considered**: Any alternative solutions you've thought of
4. **Additional Context**: Mockups, examples, or references

---

## Issue Labels

| Label | Description |
|-------|-------------|
| `bug` | Something isn't working |
| `enhancement` | New feature or improvement |
| `documentation` | Documentation improvements |
| `question` | Questions about functionality |
| `platform:ios` | iOS-specific issue |
| `platform:android` | Android-specific issue |
| `platform:web` | Web-specific issue |
| `area:wallets` | Related to financial features |
| `area:consumables` | Related to inventory features |
| `area:users` | Related to user management |
| `area:events` | Related to event features |
| `area:roles` | Related to role/permission features |

---

## Contact

For questions or support, please open an issue on this repository.
