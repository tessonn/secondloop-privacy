# Privacy Policy for SecondLoop

**Last Updated: February 8, 2026**

Thank you for using SecondLoop. This Privacy Policy explains how we collect, use, store, and protect your information when you use our iOS application. We are committed to being transparent about our data practices and respecting your privacy.

## 1. Information We Collect

### 1.1 Device Identifier

When you first launch SecondLoop, the app generates a random, anonymous string (referred to as a "Device ID") in the format `device_[timestamp][random characters]`. This identifier is created locally on your device and is used solely to associate your presets with your device. It is **not** derived from Apple's Identifier for Advertisers (IDFA), Identifier for Vendor (identifierForVendor), or any other system-level device identifier.

### 1.2 Preset Data

When you create or edit a preset, the following data is collected:

- Preset title (user-provided)
- Preparation time (seconds)
- Work time (seconds)
- Rest time (seconds)
- Number of repetitions

### 1.3 Information We Do NOT Collect

We do **not** collect any of the following:

- Personal information (name, email address, phone number, physical address)
- Location data
- Photos, contacts, or other device data
- Health or fitness data
- Analytics or usage tracking data
- Advertising identifiers

## 2. How We Use Your Information

The information we collect is used exclusively for the following purposes:

| Data | Purpose |
|------|---------|
| Device ID | To associate your presets with your device so they can be synced and retrieved |
| Preset Data | To save, sync, and display your custom interval timer configurations |

We do **not** use your data for advertising, profiling, marketing, or any purpose other than providing core app functionality.

## 3. Data Storage and Security

### 3.1 Local Storage

Your data is stored locally on your device using iOS UserDefaults. This data remains on your device and is protected by the security measures built into iOS.

### 3.2 Cloud Storage

Your data is also stored in the cloud to enable data persistence. We use **Supabase**, a hosted PostgreSQL database service, with servers located in the **AWS Asia Pacific (Tokyo, ap-northeast-1)** region. Data transmitted between your device and the cloud is encrypted in transit using TLS (Transport Layer Security). Access to the database is restricted through Row Level Security (RLS) policies tied to your Device ID.

## 4. Data Sharing and Third Parties

### 4.1 Third-Party Services

We use the following third-party service:

- **Supabase** — Used solely for cloud database storage. Supabase processes your data on our behalf and does not use it for any independent purpose. You can review Supabase's privacy policy at [https://supabase.com/privacy](https://supabase.com/privacy).

### 4.2 No Sale or Sharing of Data

We do **not** sell, rent, trade, or otherwise share your data with any third parties for advertising, marketing, analytics, or any other purpose. Your data is used exclusively to provide the app's functionality.

## 5. Data Retention

Your preset data and Device ID are retained in our cloud database for as long as you use the app. If you delete the app from your device, your locally stored data is automatically removed. Cloud-stored data may persist on our servers until you request its deletion (see Section 6).

## 6. Your Rights

You have the following rights regarding your data:

### 6.1 Data Deletion

You can request the complete deletion of all your data (including your Device ID and all associated presets) from our cloud servers by contacting us at the email address provided in Section 9. We will process your request within 30 days.

### 6.2 Local Data Deletion

You can delete all locally stored data at any time by uninstalling the app from your device.

### 6.3 Data Access

You can request a copy of the data we hold about you by contacting us at the email address provided in Section 9.

## 7. Children's Privacy

SecondLoop is suitable for users of all ages. We do **not** knowingly collect personal information from children under the age of 13 (or the applicable age in your jurisdiction). Since we do not collect any personal information from any user, there is no risk of inadvertently collecting data from children. If you believe that we have inadvertently collected data from a child, please contact us immediately and we will take steps to delete such information.

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we make changes, we will update the "Last Updated" date at the top of this policy. We encourage you to review this Privacy Policy periodically. Your continued use of the app after any changes constitutes your acceptance of the updated policy.

## 9. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us at:

**Email:** tessonn@gmail.com

---

*This Privacy Policy is effective as of February 8, 2026.*
