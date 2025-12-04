# WooCommerce Unified Reviews

## Overview
This project unifies reviews and ratings across grouped product formats (paperback, ebook, audiobook) in WooCommerce. Instead of each format showing separate counts, all reviews are aggregated and displayed consistently.

## Features
- ✅ Combined review list across grouped products
- ✅ Correct star ratings and counts in product summary
- ✅ Fixed tab titles (no more "Reviews (0)")
- ✅ Structured data override for SEO (Google sees correct counts)
- ✅ Safe child theme overrides (no core edits)

## Technical Highlights
- Custom PHP functions to query comments and ratings
- Filters: `woocommerce_product_get_average_rating`, `woocommerce_product_get_review_count`
- Template overrides: `rating.php`, `single-product-reviews.php`, `tabs.php`
- JSON-LD schema override for SEO

## Before & After
**Before:** Each format showed separate reviews, counts mismatched, SEO broken.  
**After:** Unified reviews across formats, correct counts everywhere, clean schema for Google.

## Why It Matters
This demonstrates advanced WooCommerce customization, safe theme overrides, and SEO‑aware development — perfect for real‑world publishing/e‑commerce scenarios.
