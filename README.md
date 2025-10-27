*********************************************************************************
# Getting Started

Download the above repository and copy contents of folders "admin" and "catalog" inside your opencart setup. If you are on linux, you can use below commands:

```

  rsync -a /<path_to_current_directory>/upload/admin/ /<path_to_opencart_setup>/admin/
  rsync -a /<path_to_current_direcrtory>/upload/catalog /<path_to_opencart_setup>/catalog/

 ```

 for opencart 4.x:
 Download the above repository and copy contents of "extension" containing "admin" and "catalog" folders to your opencart setup "extension" folder. If you are on linux, you can use below commands:

 ```
  rsync -a /<path_to_current_directory>/upload/extension/ /<path_to_opencart_setup>/extension/
 ```


- Go to your opencart admin console

- Click on Extensions link, present on left-hand side naviation

- Choose Payments from the drop down

- Go to "NTT DATA Payment Services India" row and click on "plus" sign to install it

- Once installed, click on edit icon to provide the configuration values

## 🪙 Set Currency to INR

To enable **Indian Rupee (INR)** as your store currency:

 1. Log in to your **OpenCart Admin Dashboard**  
 2. Navigate to **System → Localisation → Currencies**  
 3. Add or Edit the **INR (Indian Rupee)** currency  
 4. Set **Value = 1.000000** (if INR is your default currency)  
 5. Save the changes  
 6. Go to **System → Settings → Local**  
 7. Set **Default Currency** to **INR**

---

## 📱 Add Mobile Number / Phone Field in Checkout

To display and make the **telephone number** required during checkout:

 1. Go to **Admin → System → Settings**  
 2. Choose your store and click **Edit**  
 3. Open the **Option** tab  
 4. Scroll to the **Account** section  
 5. Enable both:
   - ✅ **Telephone Display**
   - ✅ **Telephone Required**

> This ensures the customer’s mobile number is captured during the checkout process.

---

## 🧹 Clear Cache After Configuration

After saving your merchant or checkout settings:

 1. Navigate to your **Admin Dashboard**  
 2. Click the **Developer Settings (gear icon)** on the top-right corner  
 3. Under **Theme Cache** and **SASS Cache**, click **Clear**

> 🧠 Clearing cache ensures all configuration changes are applied properly.

---

### 🆘 Need Help?

For support or further assistance, reach out to your payment provider or administrator.

---

**© 2025 NTTDATAPAY – Secure Payments for Smarter Businesses**