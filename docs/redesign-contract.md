# Redesign contract: Home Energy Credits

## Existing UI conventions
Keep the restrained palette, plain-language labels, keyboard access, responsive single-column behavior below 700px, and readable HTML table. Use shared state so charts, summary values, and sorted rows stay synchronized.

## Voucher status mapping
Ordered statuses: Received, Evidence check, Authorized, Paid. Do not merge or rename statuses. Derive chart counts from current records.

## Allowed sort fields
Reference, Received date, Credit value, Status. Sorting must be stable, accessible by keyboard, and visibly indicate direction.

## Scope
Redesign source components index.html, styles.css, and app.js. Preserve the synthetic records and status meanings. Do not invent redemption outcomes or financial history. Verify the deployed result in the matching Vercel project.
