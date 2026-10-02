# NOVA5

### Know it's available. Know when it arrives.

NOVA5 is a reliability-focused digital solution for NOVA CART, designed to improve product availability, delivery predictability, inventory accuracy, customer value, and repeat purchases.

## Problem Diagnosis

NOVA CART's growth is being affected by declining customer trust and operational reliability.

Key evidence from the challenge:

- Repeat purchase declined from 41% to 27%.
- Average delivery time increased from 29 to 37 minutes.
- Cancellation rate increased from 6% to 11%.
- 35% of cancellations were caused by products being unavailable.
- 29% of customers reported that products shown as available became unavailable.
- Support tickets increased from 3,100 to 5,900 per month.
- 44% of coupons were never redeemed.

These signals point to a connected reliability problem rather than a single isolated issue.

## Solution

NOVA5 connects customer experience, store inventory, and operational decision-making through five reliability pillars:

1. Availability
2. Speed
3. Accuracy
4. Value
5. Retention

The system prioritizes reliable fulfilment rather than simply showing the cheapest or fastest-looking option.

## How It Works

### Customer

The customer searches for a product and provides relevant context such as:

- Product needed
- Budget
- Urgency
- Delivery preference

NOVA5 evaluates available store/product information and provides:

- Availability confidence
- Estimated delivery time
- Inventory freshness
- Store reliability
- Recommendation reason

### Store

The store dashboard identifies products that need attention based on demand and inventory freshness.

The partner can quickly:

- Review priority products
- Verify stock
- Update inventory

### Operations

NOVA5 supports fulfilment decisions using factors such as:

- Inventory confidence
- Store reliability
- Store workload
- Delivery ETA
- Distance

This helps reduce failed fulfilment and improve delivery predictability.

## Core Logic

INPUT
→ Customer request + product/store data

PROCESSING
→ Availability confidence + inventory freshness + store reliability + delivery reliability

OUTPUT
→ Recommended fulfilment option + ETA + confidence + reason

ACTION
→ Customer can proceed with the recommended order and stores can update high-risk inventory.

## Business Impact

The intended business chain is:

Accurate inventory
→ fewer unavailable-product cancellations
→ fewer failed orders
→ more predictable delivery
→ fewer support issues
→ better customer experience
→ more customers reaching repeat orders
→ stronger retention

NOVA5 is designed to reduce dependence on blanket promotional spending by improving the underlying reliability of the customer journey.

## Technology

- HTML
- CSS
- JavaScript
- GitHub
- GitHub Pages

The prototype uses synthetic demonstration data and does not process real payments or real customer orders.

## Prototype

Live demo:

https://psaikushali.github.io/NOVA5/

Source code:

https://github.com/psaikushali/NOVA5

## Assumptions

- Store inventory data can be updated or integrated with the existing partner dashboard.
- Existing order, customer, payment, coupon and tracking systems can provide relevant signals.
- Availability confidence is calculated from inventory freshness and store reliability.
- The prototype uses simulated data to demonstrate the decision-making workflow.

## Security & Privacy

The prototype does not collect real customer payment information or sensitive personal data.

Production implementation should use authenticated APIs, authorization controls, encrypted data transmission, secure secrets management, input validation, and appropriate data-access controls.

## Accessibility

The interface is designed with responsive layouts, readable contrast, keyboard-focus considerations, and clear action labels.

## Project Status

Functional hackathon prototype — NOVA5.
