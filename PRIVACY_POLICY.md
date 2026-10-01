# Privacy Policy for Miftah ul-Islah (مفتاح الإصلاح)

**Effective Date:** September 25, 2026  
**Last Updated:** September 27, 2026  
**Application ID:** `com.warisali.miftahulislah`  
**Contact:** [mail.warisxali@gmail.com](mailto:mail.warisxali@gmail.com)  
**Privacy Policy Web Link:** [https://waris-ali-git.github.io/quran-app/](https://waris-ali-git.github.io/quran-app/)  

At **Miftah ul-Islah**, we respect and protect your privacy. This Privacy Policy explains what information our mobile application accesses, how it is used, and the measures we take to ensure your personal data remains private and secure.

---

## Scholarly Review & Institutional Verification

Miftah ul-Islah is committed to religious authenticity, doctrinal accuracy, and textual fidelity:
- **Scholarly Review by Team of Mufti Muhammad Taqi Usmani:** The religious content, Quranic texts, and Islamic references in this application have undergone scholarly review by qualified research scholars associated with the team of Justice (Retd.) Mufti Muhammad Taqi Usmani to ensure doctrinal accuracy and textual fidelity.
- **Shared with Saudi Awqaf Authorities:** To maintain rigorous standards of Islamic verification and standardization, the complete application content and resources have been shared directly with Saudi Awqaf (Islamic Affairs) authorities for institutional review, guidance, and standardization.

---

## 1. Information We Access and How We Use It

### A. Location Information (Approximate and Precise)
- **What We Access:** Approximate location (`ACCESS_COARSE_LOCATION`) and precise location (`ACCESS_FINE_LOCATION`) via GPS or network.
- **Why We Need It:**
  1. **Prayer Times (Namaz / Salah):** To calculate accurate daily prayer times (Fajr, Dhuhr, Asr, Maghrib, Isha) based on your geographic coordinates and local calculation methods.
  2. **Qibla Direction:** To accurately point the compass needle towards the Holy Ka'bah in Mecca from your current location.
  3. **Local Islamic (Hijri) Date:** To determine the correct local moon-sighting calendar date.
- **How It Is Handled:** 
  - Location coordinates are processed **on-device in real-time**.
  - We do **NOT** track your background location when the app is closed.
  - We do **NOT** store your location coordinates on any remote servers.
  - We do **NOT** sell, rent, or share your location data with third-party advertisers or data brokers.

### B. Device Notifications & Alarms
- **What We Access:** Notification permissions (`POST_NOTIFICATIONS`) and exact alarm scheduling (`SCHEDULE_EXACT_ALARM`).
- **Why We Need It:** To deliver scheduled Adhan (prayer call) reminders at the exact calculated prayer times, and optional daily Quran / worship reminders.
- **How It Is Handled:** All scheduling is performed locally on your device using Android system alarm and notification managers. You can enable, disable, or customize these notifications at any time in the app settings.

### C. Local Storage & Audio Caching
- **What We Access:** Local app cache and device internal storage.
- **Why We Need It:** To cache downloaded Quran recitations, Tafseer audio files, Qaida pronunciation audio, and user preferences (bookmarks, reading progress, notes).
- **How It Is Handled:** Data is stored locally in the application's private sandboxed storage and is deleted automatically if you clear application data or uninstall the app.

---

## 2. Third-Party Services & Data Sharing

Miftah ul-Islah is designed with a **privacy-first** philosophy:
- **No Third-Party Advertising:** The application contains zero advertisements and zero ad-tracking SDKs.
- **No Analytics / User Profiling:** We do not collect behavioral tracking, user telemetry, or device identifiers.
- **Open Geographic APIs:** When reverse-geocoding coordinates to show city names or fetching prayer timing tables, minimal non-personally identifiable requests are made via standard HTTPS APIs (such as AlAdhan API and OpenStreetMap Nominatim) strictly to fulfill the requested feature.

---

## 3. Data Retention and Deletion

- Because **Miftah ul-Islah** does not operate remote user accounts or store user data on cloud servers, all your bookmarks, notes, and preferences reside solely on your device.
- You have complete control over your data. To permanently delete all stored data, you can simply use the "Clear Data" option in your device settings or uninstall the app.

---

## 4. Children’s Privacy

Miftah ul-Islah is safe for all ages. We do not knowingly collect or solicit personal information from children under the age of 13.

---

## 5. Permissions Summary Table

| Permission | Category | Purpose | Stored Remotely? |
| :--- | :--- | :--- | :--- |
| `ACCESS_FINE_LOCATION` | Location | High-accuracy Qibla compass alignment & prayer calculations | **No** (Processed locally) |
| `ACCESS_COARSE_LOCATION` | Location | City-level prayer times calculation | **No** (Processed locally) |
| `POST_NOTIFICATIONS` | Notifications | Timely prayer (Adhan) reminders | **No** (Local notification) |
| `SCHEDULE_EXACT_ALARM` | System Alarms | Precise Adhan trigger at prayer times | **No** (Local alarm) |
| `RECEIVE_BOOT_COMPLETED` | System | Reschedule prayer notifications after device reboot | **No** (On-device service) |

---

## 6. Changes to This Privacy Policy

We may update our Privacy Policy periodically to reflect new features or legal requirements. Any modifications will be posted to this page with an updated "Last Updated" date.

---

## 7. Contact Us

If you have any questions or feedback regarding this Privacy Policy, please contact:

- **Developer Contact:** [mail.warisxali@gmail.com](mailto:mail.warisxali@gmail.com)
