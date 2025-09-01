# Rental PS App - Requirements Specification

## 1. DISPLAY REQUIREMENTS
- Must run on Android (S20+ specifically)
- Support Samsung Dex with 1080p external monitor output
- Real-time timer display for customers
- Dual timer modes: count-up (from 0) and count-down (from X hours)
- Display remaining time and total cost simultaneously
- Color-coded status: green (available), red (occupied)

## 2. TIMER BOARD COMPONENT
- Interactive board for each PS unit
- Large, clear display for customer viewing
- Color-changing background based on status
- "Add/Open" button for occupied units
- Popup modal for time input when button pressed
- Ability to add F&B items to rental directly from board
- Real-time cost calculation display

## 3. DATABASE REQUIREMENTS
- Comprehensive inventory management:
  - PS units database (specs, purchase date, status)
  - TV units database (linked to PS units)
  - F&B inventory tracking (stock, pricing, categories)
- Financial tracking:
  - Daily revenue calculation
  - Inflation calculation capabilities
  - Depreciation tracking for equipment
  - Expense and profit tracking

## 4. REPORTING SYSTEM
- Automated daily reports generation
- Excel export functionality (.xlsx format)
- Customizable report periods (daily, weekly, monthly)
- Financial summaries including:
  - Rental income
  - F&B sales
  - Equipment depreciation
  - Net profit calculations

## 5. F&B MANAGEMENT MODULE
- Dedicated F&B management section
- Real-time stock level monitoring
- Low stock alerts and notifications
- Easy stock addition/update interface
- Sales tracking per item
- Profit margin calculation for F&B items

## 6. RENTAL MANAGEMENT FEATURES
- One-click rental start/stop functionality
- Flexible time input (hours/minutes)
- Automatic cost calculation based on:
  - Time duration
  - PS unit pricing tier
  - Additional F&B items
- Receipt generation for customers
- Payment tracking (cash/digital)

## 7. TECHNICAL REQUIREMENTS
- Android-native application
- Samsung Dex compatibility
- Offline capability for reliability
- Local database with cloud sync option
- Backup and restore functionality
- Multi-user support with role permissions

## 8. USER INTERFACE REQUIREMENTS 
- Touch-friendly large buttons
- High contrast display for monitor viewing
- Responsive design for various screen sizes
- Simple navigation between functions
- Real-time data updates without page refresh