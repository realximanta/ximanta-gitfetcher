<div align="center">

# 🚀 Ximanta GitFetcher

**Paste a GitHub repo URL. Get every file. Flattened. One tap. Done.**

[![Build APK](https://github.com/realximanta/ximanta-gitfetcher/actions/workflows/build-app.yml/badge.svg)](https://github.com/realximanta/ximanta-gitfetcher/actions/workflows/build-app.yml)
[![Release](https://img.shields.io/github/v/release/realximanta/ximanta-gitfetcher?include_prereleases&style=flat-square&color=blue)](https://github.com/realximanta/ximanta-gitfetcher/releases)
[![Downloads](https://img.shields.io/github/downloads/realximanta/ximanta-gitfetcher/total?style=flat-square&color=brightgreen)](https://github.com/realximanta/ximanta-gitfetcher/releases)
[![Stars](https://img.shields.io/github/stars/realximanta/ximanta-gitfetcher?style=flat-square&color=yellow)](https://github.com/realximanta/ximanta-gitfetcher/stargazers)

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com)
[![Language](https://img.shields.io/badge/Kotlin-2.0.20-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![UI](https://img.shields.io/badge/Jetpack-Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Min SDK](https://img.shields.io/badge/minSdk-26-orange?style=for-the-badge)](https://developer.android.com)
[![Target SDK](https://img.shields.io/badge/targetSdk-34-blue?style=for-the-badge)](https://developer.android.com)

[![Made by Ximanta](https://img.shields.io/badge/Made%20by-Ximanta-9C27B0?style=for-the-badge&logo=github&logoColor=white)](https://github.com/realximanta)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)](https://github.com/realximanta/ximanta-gitfetcher/pulls)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://github.com/realximanta/ximanta-gitfetcher)

</div>

---

## Project overview

Ximanta GitFetcher is a tiny Android app that takes a GitHub repository URL, walks the entire file tree (no matter how deeply nested), and dumps every single file into one flat list on the device. The app is optimized for quick inspection and bulk-download of repository files directly from your phone — no folder hunting or manual downloads required.

This README now includes a short quickstart and clearer usage guidance so new users can get running immediately.

---

## 🧠 What is this?

**Ximanta GitFetcher** is a tiny Android app that takes a GitHub repository URL,
walks the entire file tree (no matter how deeply nested), and dumps **every single
file into one flat list** — right on your phone.

No folder hunting. No "where did that file go?". Just:

> Paste URL → Fetch → Download one, or Download All.

---

## 📱 Screenshots — Full Walkthrough

Follow the app from install to "all files downloaded":

### 1 · Install the APK

<p align="center">
  <img src="Screenshot_2026-10-15-00-07-07-887_com.google.android.packageinstaller.jpg" width="280" alt="Installing Ximanta GitFetcher"/>
</p>

<p align="center"><em>Android's package installer verifies and installs the APK — no Play Store required.</em></p>

---

### 2 · Terms & Conditions

<p align="center">
  <img src="Screenshot_2026-10-15-00-07-37-231_com.ximanta.gitfetcher.jpg" width="280" alt="Terms screen top"/>
</p>

<p align="center"><em>Branded hero with the Ximanta logo, wordmark, and 5-point terms.</em></p>

<p align="center">
  <img src="Screenshot_2026-10-15-00-07-39-608_com.ximanta.gitfetcher.jpg" width="280" alt="Terms screen bottom with Agree button"/>
</p>

<p align="center"><em>Tick the checkbox to unlock the violet <strong>AGREE &amp; CONTINUE</strong> button.</em></p>

---

### 3 · Repository URL Entry

<p align="center">
  <img src="Screenshot_2026-10-15-00-07-48-377_com.ximanta.gitfetcher.jpg" width="280" alt="URL screen empty"/>
</p>

<p align="center"><em>Empty state — paste a link, tap the clipboard icon, or pick an example.</em></p>

<p align="center">
  <img src="Screenshot_2026-10-15-00-07-52-413_com.ximanta.gitfetcher.jpg" width="280" alt="URL screen valid"/>
</p>

<p align="center"><em>Live parsing — the moment the URL is valid, the chip lights up green and the button becomes <strong>Fetch ximanta-gitfetcher</strong>.</em></p>

---

### 4 · File List

<p align="center">
  <img src="Screenshot_2026-10-15-00-08-00-347_com.ximanta.gitfetcher.jpg" width="280" alt="Files list top"/>
</p>

<p align="center"><em>Every file, flattened. <strong>34 files · 169.3 KB</strong> with the summary bar, live filter, and a ⬇ button on every row.</em></p>

<p align="center">
  <img src="Screenshot_2026-10-15-00-08-05-104_com.ximanta.gitfetcher.jpg" width="280" alt="Files list scrolled"/>
</p>

<p align="center"><em>Scroll to the bottom for the <strong>Download All Files</strong> panel — 34 files, 169.3 KB total.</em></p>

---

### 5 · Download Progress

<p align="center">
  <img src="Screenshot_2026-10-15-00-08-12-875_com.ximanta.gitfetcher.jpg" width="280" alt="Downloading in progress"/>
</p>

<p align="center"><em>Sequential bulk download with a live progress bar and a <strong>2 saved</strong> counter chip.</em></p>

<p align="center">
  <img src="Screenshot_2026-10-15-00-08-35-164_com.ximanta.gitfetcher.jpg" width="280" alt="All files downloaded"/>
</p>

<p align="center"><em>All <strong>34 files saved</strong> — checkmarks on every row, snackbar confirms the destination, button becomes <strong>Re-download All</strong>.</em></p>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔗 **Smart URL parsing** | Accepts `https://github.com/user/repo`, `...repo.git`, `github.com/user/repo`, `git@github.com:user/repo.git` |
| 📂 **Recursive flattening** | Files nested 10 folders deep appear exactly like root-level files |
| ⬇️ **Per-file download** | A download button sits on the right of every single file row |
| 📦 **Download All** | One button at the bottom of the list grabs everything |
| 🔍 **Live search filter** | Filter hundreds of files instantly |
| 🔐 **Terms gate** | User must accept Terms & Conditions before entering the app |
| 🎨 **Ximanta branding** | Custom vector logo, custom adaptive launcher icon |
| 🌗 **Dark / Light theme** | Follows system theme automatically |
| 💾 **Scoped storage safe** | Uses `MediaStore` on Android 10+, legacy file API below that |
| 🤖 **CI-built APK** | Every Release automatically builds and attaches the APK |

---

## 🚀 Quickstart (1 minute)

1. Install the APK from Releases or build it via Actions (see the badge at the top).
2. Open the app and accept Terms & Conditions.
3. Paste a GitHub repository URL into the entry field (or tap the clipboard icon).
4. Tap "Fetch <repo-name>" — the app reads the repository tree and lists every file.
5. Tap the ⬇ button on any file to download it, or use "Download All" to save everything.

This quick path is sufficient for trying the app immediately. See the full "How to Build" section below for repository-source build steps using the GitHub website.

---

## 🚀 How to Build (100% through the GitHub website)

### Step 1 — Create the repository
1. Go to <https://github.com/new>
2. Name it **`ximanta-gitfetcher`**
3. Set it **Public**, click **Create repository**

### Step 2 — Add every file
For each file in this guide:
1. Click **Add file → Create new file**
2. Type the **full path** (e.g. `app/src/main/java/com/ximanta/gitfetcher/MainActivity.kt`) — typing `/` creates folders automatically
3. Paste the content
4. Click **Commit changes**

### Step 3 — Draft a new release
1. Go to **Releases → Draft a new release**
2. **Choose a tag** → type `v1.0.0` → *Create new tag*
3. Title: `Ximanta GitFetcher v1.0.0`
4. Click **Publish release**

### Step 4 — Watch the magic
The workflow at `.github/workflows/build-app.yml` fires automatically.

- Go to the **Actions** tab
- Wait ~3–5 minutes
- Go back to your **Release** — the APKs are attached 🎉

You can also trigger it manually: **Actions → Build APK → Run workflow**.

---

## 📦 Download Locations

| Android version | Where files go |
|---|---|
| Android 10+ (API 29+) | `Downloads/Ximanta/<repo-name>/` |
| Android 8 – 9 (API 26–28) | `Downloads/Ximanta/<repo-name>/` |

All files are **flattened**. A file at `src/main/java/Foo.kt` is saved as:

```
src_main_java_Foo.kt
```

This keeps the original path readable while living in a single flat folder — exactly
as requested.

---

## 🔐 Permissions

| Permission | Why | When |
|---|---|---|
| `INTERNET` | Talk to `api.github.com` and `raw.githubusercontent.com` | Always |
| `ACCESS_NETWORK_STATE` | Detect offline state | Always |
| `WRITE_EXTERNAL_STORAGE` | Save files to Downloads | Android ≤ 9 only |
| `READ_EXTERNAL_STORAGE` | Legacy storage read | Android ≤ 12 only |

On **Android 10+** no runtime storage permission is needed — the app uses
`MediaStore.Downloads`, which is the officially sanctioned scoped-storage path.

---

## 🛠 Tech Stack

| Layer | Choice |
|---|---|
| Language | Kotlin 2.0.20 |
| UI | Jetpack Compose (Material 3) |
| Networking | OkHttp 4.12 |
| Async | Kotlin Coroutines |
| JSON | `org.json` (zero extra deps) |
| Build | AGP 8.5.2 · Gradle 8.7 |
| CI | GitHub Actions |
| Min SDK | 26 (Android 8.0) |
| Target SDK | 34 (Android 14) |

---

## 🧩 How the API works

1. `GET https://api.github.com/repos/{owner}/{repo}` → reads `default_branch`
2. `GET https://api.github.com/repos/{owner}/{repo}/git/trees/{branch}?recursive=1`
   → returns **every blob in the whole tree in one call**
3. `GET https://raw.githubusercontent.com/{owner}/{repo}/{branch}/{path}`
   → raw bytes for each file

> **Rate limits:** unauthenticated GitHub API allows 60 requests/hour per IP.
> Downloading files uses `raw.githubusercontent.com`, which is **not** rate-limited
> the same way — so "Download All" on a 500-file repo works fine.

---

## 🐛 Troubleshooting

| Problem | Fix |
|---|---|
| `Repo not found (404)` | Repo is private or the URL has a typo |
| `Failed to read tree (403)` | GitHub API rate limit hit — wait an hour |
| APK not in Releases | Check the **Actions** tab for a red ❌ and read the log |
| Build fails on `compileSdk` | Make sure you didn't edit `app/build.gradle.kts` |
| Files land nowhere | Grant storage permission when prompted (Android 9 and below only) |

---

## 📜 License

MIT — do whatever you want, just don't blame me.

---

<div align="center">

**Built with ❤️ by [Ximanta](https://github.com/realximanta)**

⭐ Star this repo if it saved you time.

</div>
