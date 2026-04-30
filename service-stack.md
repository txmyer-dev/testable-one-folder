# Service Stack (The 50-User Engine)

To maintain a high-margin $750/week model for 50 users, we use a "Single Pane of Glass" approach.

## 1. The Engine: Syncro MSP
Syncro is our primary tool because it combines RMM, PSA, and Billing into one flat monthly cost for us.
*   **RMM:** Automated patching and scripting for all 50+ endpoints.
*   **PSA:** All ticketing and communication.
*   **Automated Billing:** Syncro is connected to **Stripe**. It automatically charges the client $750 every Monday morning.
*   **Remote Access:** Using the integrated Splashtop/ScreenConnect for instant support.

## 2. The Insurance: Huntress (CYA)
We include Huntress as our "Silent Partner" to provide 24/7 protection that we cannot provide alone.
*   **Managed EDR:** Human SOC monitoring for all workstations.
*   **Identity Protection:** Monitoring M365 for Business Email Compromise.
*   **Auto-Isolation:** If a machine is breached at 2 AM, Huntress kills its internet access automatically.

## 3. The Protection: Bitdefender
Integrated directly into the Syncro agent.
*   **Role:** Standard "shield" for known viruses and web filtering.

## 4. The Knowledge: Hudu
*   **Role:** The "Vault." Stores every password, serial number, and network map for the client.

## 5. The Add-On Delivery
*   **Web/Marketing:** WordPress + GoHighLevel (for CRM/Sales automation).
