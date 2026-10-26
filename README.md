<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.png">
    <img src="assets/logo-light.png" alt="ZestBill - Billing made simple" width="380">
  </picture>
</p>

# ZestBill

GST billing and payment tracking for small shops and businesses. ZestBill is a Windows desktop app that works fully
offline, and your data stays in one file on your own computer.

## Download

**[Get the latest version](https://github.com/yaseenShaik1432/zestbill-releases/releases/latest)**, then download
`ZestBill-Setup-<version>.exe` from the **Assets** list.

Requires Windows 10 or later (64-bit).

> This repository only holds the installers. There is no source code here.

## Install

1. Double-click **ZestBill-Setup-&lt;version&gt;.exe**.
2. If Windows shows **"Windows protected your PC"**, click **More info → Run anyway**.
3. Choose where to install (the default is fine) and finish. A **ZestBill** icon appears on your desktop.
4. Open ZestBill and answer a few questions about your business. It takes about 2 minutes.

## What it does

- GST tax invoices with HSN/SAC, CGST + SGST or IGST worked out from the place of supply, round-off and amount in words.
- Full and part payments, overdue tracking, a Payments Due list and customer statements.
- Print an A4 tax invoice or a 58/80 mm thermal receipt, or save it as a PDF. Unpaid invoices get a UPI "scan to pay" QR code.
- Share invoices, payment reminders and statements on WhatsApp.
- Products with HSN, price and GST, CSV import, and optional stock tracking with low-stock warnings.
- Reports for sales, GST and payments received, with CSV export for your accountant.
- Daily automatic backups, and optional PIN lock.

## Free trial and license

ZestBill is free to try for **14 days**. After that it becomes read-only until you enter a license key: you can still
view and print invoices, record payments and make backups, but you can't create new invoices.

To get a key, open **Settings → License**, copy your **Machine ID** and send it to your ZestBill provider. Keys work
offline and are tied to one computer.

## Updates

ZestBill looks for new versions here on GitHub, either automatically or when you choose **Help → Check for Updates…**.
It never installs an update by itself: you decide when. Your data is backed up first.

Each release also contains a `.blockmap` file and a `latest.yml` file. The app uses these to update itself, so you don't
need to download them.

## Your data

| What              | Where                                          |
| ----------------- | ---------------------------------------------- |
| Database          | `%APPDATA%\ZestBill\zestbill.db`               |
| Automatic backups | `Documents\ZestBill Backups\` (daily, 30 days) |
| PDFs for WhatsApp | `Documents\ZestBill Invoices\`                 |

Your business data is stored on your own computer. To move to a new computer, make a backup in
**Settings → Backup & restore**, install ZestBill on the new computer and restore it there.

## Coming from Easy Billing?

ZestBill was previously called Easy Billing. It installs as a separate app and does not replace Easy Billing, so your
old data is not touched. To bring your data across:

1. In Easy Billing, go to **Settings → Backup & restore → Back up to pen drive / other folder…** and save the file
   somewhere safe.
2. Install ZestBill and finish the first-time setup.
3. In ZestBill, go to **Settings → Backup & restore → Restore from a backup file…** and choose that file.
4. Go to **Settings → License** and send your new Machine ID to your ZestBill provider for a new license key. Old
   Easy Billing keys do not work in ZestBill.
5. When everything looks right, uninstall Easy Billing. Uninstalling does not delete its data.
