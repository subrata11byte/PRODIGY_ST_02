# PRODIGY_ST_02  
## Task 2: Compatibility Testing Report – SHOPLANE Website  

---

## Objective  

To conduct compatibility testing of the SHOPLANE website across multiple browsers and device views in order to identify layout issues, broken links, and functionality discrepancies.

---

## Test Environment  

**Browsers Tested:**  
- Google Chrome (Desktop)  
- Microsoft Edge (Desktop & Mobile View)  
- Mozilla Firefox (Desktop & Mobile View)  

**Devices Tested:**  
- Desktop (Windows)  
- Mobile View (Browser Developer Tools Simulation)  

---

## Detailed Findings  

### 1. Layout Compatibility  

- The website loads properly in all tested browsers.  
- No major layout distortion was observed.  
- Mobile view is responsive.  
- Images and product cards are displayed correctly.  

**Status:** Layout is compatible across tested platforms.

---

### 2. Navigation & Broken Links  

The following navigation issues were observed across all browsers and devices:

- The **“CLOTHING”** tab leads to a 404 Page Not Found error (Netlify error page).
- The **“ACCESSORIES”** tab leads to a 404 Page Not Found error.
- Footer links such as **Men Clothing**, **Women Clothing**, etc., are not functional.

**Impact:** Core navigation links are broken, affecting user experience.

---

### 3. Search and Profile Functionality  

- The search bar does not return results when used.
- The profile button is visible but does not perform any action.

**Impact:** Key interactive features are non-functional.

---

### 4. Product and Cart Functionality  

- Product pages open correctly when clicked.
- “Add to Cart” functionality works properly.
- Cart displays selected items correctly.

---

### 5. Checkout Process Issues  

The following issues were observed during order placement:

- No option to select size or color for products.
- No form to collect user details (name, address, email).
- No payment process is initiated.
- The order is confirmed immediately after clicking “Place Order”.
- The system displays a message stating that order details will be sent via email, even though no email was collected.

**Impact:** The checkout process is incomplete and does not follow standard e-commerce flow.

---

## Compatibility Conclusion  

The SHOPLANE website maintains visual consistency across Chrome, Edge, and Firefox in both desktop and mobile views. No major layout compatibility issues were observed.

However, several functional defects and broken navigation links were identified. These issues are consistent across all tested browsers, indicating application-level problems rather than browser-specific compatibility issues.

---

## Recommendations  

1. Fix broken navigation links for CLOTHING, ACCESSORIES, and footer sections.  
2. Implement functional search capability.  
3. Activate or properly configure the profile feature.  
4. Add product attribute selection options (size, color).  
5. Implement a complete checkout process including:
   - User information form  
   - Email validation  
   - Payment gateway integration  
6. Prevent order confirmation unless required details are provided.
