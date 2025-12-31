# Fallen Follow Registry

**Fallen Follow Registry** is a simple, private tool that shows who you follow on Instagram that **don’t** follow you back.  
Logging every follow that didn’t follow through.

You just open `index.html`, upload two files from your Instagram download, and it shows you a list. No coding needed. It works on desktop, tablets, and modern mobile browsers.

---

## What it does

- You ask Instagram for a copy of your data.
- Inside that download are two files:
  - One with people who **follow you**.
  - One with people you are **following**.
- This page compares them and shows:
  - Everyone you follow.
  - Who **do not** follow you back.

Nothing is uploaded anywhere. The files stay in your browser on your device.

---

## What you need

- An Instagram account.
- A computer (Mac or Windows), **tablet**, or **phone** with a modern browser.
- A browser (Chrome, Edge, Firefox, Safari, or mobile equivalents).
- Your Instagram data download (JSON), which includes:
  - `followers_1.json`
  - `following.json` (or `following_1.json`)

On phones and tablets, the layout adapts, and heavy background animations are disabled to keep things smooth.

---

## Step 1 – Get your Instagram files

1. Go to **instagram.com** (or the Instagram app) and log in.
2. Open **Settings → Accounts Center**.
3. Go to **Your information and permissions → Export your information**.
4. Click or tap **Create export**.
5. Choose:
   - Your account
   - **All time**
   - **Format: JSON**
   - Under **Connections**, make sure **Followers and following** is checked.
6. Confirm and wait for Instagram’s email/notification.
7. When it’s ready, download the **ZIP file** to your computer, tablet, or phone.

If you export on your phone, it’s easiest to move the ZIP to a computer or tablet to unzip and pick out the JSON files.

---

## Step 2 – Find `followers_1.json` and `following.json`

1. Open your **Downloads** folder.
2. Find the Instagram ZIP you just downloaded.
3. Extract/unzip it.
4. Open the new folder, then go into:
   - `connections`
   - `followers_and_following`
5. In there, you should see something like:
   - `followers_1.json`
   - `following.json` (or `following_1.json`)

You’ll upload these two files into the tool.

---

## Step 3 – Download and open this tool from GitHub

You’re already on the GitHub page for this project.

1. At the top of this page, click the green **Code** button.
2. Click **Download ZIP**.
3. When the ZIP finishes downloading, open your **Downloads** folder.
4. Find the ZIP (for example, `fallen-follow-registry-main.zip`) and extract it.
5. Open the extracted folder.
6. Find **`index.html`**.
7. Double‑click `index.html` (desktop/laptop) or open it in your browser (tablet/phone).

Your browser will open a page that says **FALLEN FOLLOW REGISTRY** with the subtitle “Logging every follow that didn’t follow through.” On tablets and phones, the layout is narrower and scrollable, and the animated glow is automatically toned down or disabled.

---

## Step 4 – Upload your Instagram files

On the Fallen Follow Registry page:

1. Find **Upload your JSON files**.
2. Click or tap **Choose files**.
3. Pick `followers_1.json` and confirm.
   - The pill next to `followers_1.json` should change to **Uploaded**.
4. Click or tap **Choose files** again.
5. Pick `following.json` (or `following_1.json`) and confirm.
   - That pill should also change to **Uploaded**.
6. When both say **Uploaded**, click or tap **Build Fallen Follows list**.

---

## Step 5 – Use the list

You’ll see:

- How many people don’t follow you back.
- A table of those accounts (horizontally scrollable on smaller screens).

For each row, you can:

- **Search** by username using the search box.
- **Open** their profile in a new tab.
- **Copy** their profile link.
- Mark them with buttons like:
  - **Unfollowed**
  - **Influencer/Celeb**
  - **News**
  - **Meme Page**
  - **Other**

These tags are just for organizing the page. They do not change anything on Instagram. On tablets and phones, all controls remain usable with touch.

---

## Privacy

- Your JSON files never leave your device.
- The page runs only in your browser.
- No log‑in, no server, no database.

If you close the tab, you’ll just need to upload the two files again next time.
