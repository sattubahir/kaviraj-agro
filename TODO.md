# TODO: Fix Dashboard Sales Update and Add Monthly Sales View

## Tasks
- [x] Update billing.html: Replace 'savedBills' with 'bills' in localStorage operations
- [x] Update billing.html: Change bill object properties (id -> billNo, customer -> customerName)
- [x] Update billing.html: Update renderSavedBills to use bill.billNo and bill.customerName
- [x] Update index.html: Add new Monthly Sales stat card, change grid to md:grid-cols-5
- [x] Update index.html: Add monthly sales calculation in loadDashboard
- [x] Update index.html: Update today's sales table to use correct bill properties
- [x] Test: Create bill, verify dashboard updates today's and monthly sales
