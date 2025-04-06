# Shopify Theme - Recommended Products Section Implementation

## Overview:
This project enhances the Shopify Product Detail Page (PDP) by adding a dynamic *Recommended Products* section using Shopify Metafields.

Recommended products are fetched dynamically and displayed beautifully in a responsive slider/carousel with reusable product cards.

---

## Features Implemented:

- Fetching Recommended Products using Shopify Metafields.
- Custom Product Card design.
- Responsive Slider with navigation buttons.
- Mobile-friendly design with media queries.
- Error Handling for empty products.
- Optimized Images with lazy loading for better performance.
- Clean & Minimal UI/UX.

---

## Added Files & Their Purpose:

| File Path | Purpose |
|-----------|---------|
| sections/recommended-products.liquid | Logic to fetch & display recommended products with slider. |
| snippets/product-card.liquid | Reusable snippet for displaying individual product cards. |
| assets/base.css | Custom CSS for styling, responsiveness & slider related styles. |

---

## Metafield Details:

Added metafield to product from Shopify Admin:

| Namespace | Key                  | Value Type |
|-----------|-----                 |------------|
| custom    | recommended_products | Product List |

→ Shopify Admin → Settings → Custom Data → Products → Add Definition  
(Then assign products from product detail page under metafields section)

---

## Complete Steps to Upload Theme on Shopify:

### Step 1: Clone Github Repository Locally

```bash
git clone https://github.com/sohail1822/Shopify_App
cd Shopify_App
