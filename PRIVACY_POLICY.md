# Privacy Policy

**Effective Date:** October 18, 2026  
**Last Updated:** October 18, 2026  

This Privacy Policy explains how **Debloater (System App Remover)** ("we", "our", or "the app"), developed by Santhosh Subramani, collects, uses, and protects information when you use our mobile application.

---

## 1. Overview & Core Philosophy

Debloater is designed to help users manage, disable, uninstall, and restore system applications and bloatware on Android devices using Shizuku or root privileges. 

We respect your privacy. **We do not collect any Personally Identifiable Information (PII)** such as your name, email address, phone number, contacts, photos, or personal files. All package removal and management operations execute locally on your device.

---

## 2. Information We Collect and Why

To ensure the app operates reliably, diagnose silent failures, and improve user experience, we collect limited, non-personal diagnostic and usage information through standard industry services.

### A. Usage Telemetry & Operational Analytics (Firebase Analytics)
We use **Google Analytics for Firebase** to understand how the app performs and where users encounter blockers. The data collected is anonymous, aggregated, and includes:
* **Feature interactions:** Taps on actions (e.g., uninstall, keep data, disable, restore, clear data).
* **Operation outcomes:** Whether an app removal or restore succeeded or failed, and the execution duration (in milliseconds).
* **Shizuku readiness:** Anonymized status indicators (e.g., whether Shizuku is ready, not installed, not running, or permission denied) to identify onboarding friction.
* **App performance metrics:** Time taken to query installed system packages and whether a query timed out.
* **Basic device attributes:** Device model, brand, manufacturer, and Android OS version.

### B. Diagnostic & Crash Reporting (Firebase Crashlytics)
To fix bugs and eliminate silent failures that degrade app performance, we use **Firebase Crashlytics**. When an operation fails or the app encounters an issue, Crashlytics records:
* **Shell failure reasons:** Specific Android Package Manager failure codes (such as `DELETE_FAILED_INTERNAL_ERROR`, `DELETE_FAILED_DEVICE_POLICY_MANAGER`, or `DELETE_FAILED_USER_RESTRICTED`) along with the target package name.
* **Device state at failure:** Android SDK level, device manufacturer, model, and network connectivity state (online/offline).
* **Stack traces:** Technical error logs indicating where in the code an error occurred.

All sensitive text is automatically redacted before transmission to prevent incidental collection of private information.

### C. In-App Purchases & Subscriptions (RevenueCat & Google Play Billing)
If you purchase an optional subscription or in-app upgrade:
* Financial and payment data (credit card numbers, billing addresses) is handled entirely by **Google Play Billing**. We never receive, process, or store your payment details.
* We use **RevenueCat** to verify purchase receipts and activate entitlements across sessions. RevenueCat receives an anonymous app user identifier and receipt tokens.

### D. Advertising (Google AdMob)
For users using the free version of the app:
* We display advertisements provided by **Google Mobile Ads (AdMob)**.
* AdMob may use device advertising identifiers (such as the Google Advertising ID / GAID) and coarse location data to serve relevant ads in accordance with Google's advertising policies.
* Premium subscribers have all advertisements disabled.

---

## 3. Local On-Device Package Management

All privileged operations (such as `pm uninstall`, `pm disable-user`, and `cmd package install-existing`) are executed directly on your device through Android's local command-line interface via Shizuku. 
* We do **not** upload or inspect your installed application data, files, or personal databases.
* The community debloat definitions (UAD lists) are fetched from public repositories (such as GitHub) and cached locally on your device.

---

## 4. Third-Party Service Providers

Our application integrates with trusted third-party services that process data in accordance with their respective privacy policies:

* **Google Play Services:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
* **Google Analytics for Firebase:** [https://firebase.google.com/policies/analytics](https://firebase.google.com/policies/analytics)
* **Firebase Crashlytics:** [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)
* **Google AdMob:** [https://policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)
* **RevenueCat:** [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy)

---

## 5. Data Retention & Security

* **Local Storage:** Your removal history and custom settings are stored locally on your device and can be erased at any time by clearing app data or uninstalling the app.
* **Telemetry Data:** Analytics and crash logs collected by Firebase are retained according to standard Google Firebase data retention schedules (typically 2 to 14 months) and are protected using industry-standard encryption protocols in transit and at rest.

---

## 6. Children's Privacy

Our application does not address anyone under the age of 13. We do not knowingly collect personal identifiable information from children under 13.

---

## 7. Changes to This Privacy Policy

We may update our Privacy Policy periodically to reflect app updates, new features, or legal requirements. Any modifications will be posted to this page with an updated "Last Updated" date.

---

## 8. Contact Us

If you have any questions, concerns, or feedback regarding this Privacy Policy or your data, you can open an issue on our GitHub repository or contact us:

* **GitHub Issues:** [https://github.com/santhosh-D-subramani/Debloater/issues](https://github.com/santhosh-D-subramani/Debloater/issues)
* **Developer Website:** [https://santhoshdsubramani.in](https://santhoshdsubramani.in)
