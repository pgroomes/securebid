SecureBid Mobile CRM Section Demos

Open index.html on a phone or computer. Each CRM section has its own mobile-first page.

New quote cover page feature:
- coverpage.html lets you upload a cover graphic
- set a cover title, subtitle, and footer text
- branding.html continues to manage company logo and quote branding
- quotes.html now generates a front cover page before the quote body

These are standalone front-end demonstrations. Production requires hosting, authentication,
database storage, secure file storage, server APIs, and live QuickBooks OAuth integration.

New backend pricing module:
- Parts catalog
- Unit cost
- Target margin
- Calculated sell price
- Labor base wage
- Labor burden percentage
- Total labor cost per hour
- Labor margin
- Calculated bill rate
- Quote cost, sell price, gross profit, and blended margin demo

New quote read-receipt module:
- Secure quote-link generation demo
- Automatic Viewed status on open
- First-open timestamp
- Last-open timestamp
- View count
- Customer name and email association
- CRM dashboard receipt log

Production requirement:
Reliable read receipts require hosted quote pages. Email read receipts and tracking pixels
can be blocked by privacy protections, image blocking, and mail clients, so the production
system should treat opening the secure quote page as the authoritative read event.

Internal work-order module:
- Separate from customer CRM
- Internal job and work-order numbers
- Technician assignments
- Scheduling and priority
- Scope of work
- Status tracking
- Labor hours
- Parts used
- Technician notes
- Field photo uploads
- Completion sign-off
- Technician roster
- Internal operations dashboard

Technician profile builder:
- Full name and employee/contractor ID
- Role and employment type
- Phone and email
- Territory and availability
- Skills and certifications
- Base cost and internal bill rate
- Emergency contact
- Internal notes
- Profile photo
- Technician documents
- Assignment history

Customer portal:
- Account overview
- Quotes and proposal approvals
- Invoices and payments
- Customer-visible work-order status
- Documents
- Support requests
- Account profile management
- Separate customer-facing access from internal CRM and technician operations
