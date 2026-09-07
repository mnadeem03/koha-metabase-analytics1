# Koha Metabase Analytics

Ready-to-use Metabase package with pre-built **Koha** dashboards and reports.

Made for librarians (no technical knowledge required).

---

## How to Install (Very Simple)

### Step 1 – Download the files

1. Click the green **Code** button → **Download ZIP**
2. Go to the **Releases** section (right side of this page)
3. Download the full `.zip` file

### Step 2 – Prepare the folder

1. Extract the ZIP file you downloaded

### Step 3 – Start Metabase

Double-click **`start-metabase.bat`**

Wait 30–60 seconds until it says Metabase is ready.

### Step 4 – Open & Login

Go to: **http://localhost:3000**

**Temporary Login:**

- **Email:** `admin@example.com`
- **Password:** `LibraryTemp2026!`

### Step 5 – Change Password (Important!)

1. Click your name at the top-right corner
2. Click **Account settings**
3. Go to the **Password** tab
4. Change the password to something only you know
5. Click **Save**

---

## How to Stop Metabase

Double-click **`shutdown-metabase.bat`**

---

## What is included?

- Pre-designed Koha dashboards and reports
- Simple start and stop buttons
- Portable Java (no need to install Java separately)

---

## How to Connect Your Koha Database (Important for Real-time Data)

For the best real-time analysis, you should connect Metabase to your live Koha database.

### Recommended Method:

1. Ask your system administrator or IT person to create a **read-only** user account in your Koha MySQL / MariaDB database.
2. Open Metabase and go to **Admin** → **Databases** → **Add a database**.
3. Select **MySQL** (or MariaDB).
4. Enter the following details of the read-only user:
   - Host
   - Port (usually 3306)
   - Database name (usually `koha_library` or similar)
   - Username
   - Password
5. Click **Save**.
6. Wait a few moments while Metabase scans the database.

After the connection is successful, all the pre-built Koha dashboards will become active and show live data.

> **Note:** Using a read-only user is strongly recommended for security reasons.

---

## Notes

- Change the temporary password immediately after first login.
- This package is intended for library staff use.
- For questions, contact the person who shared this package with you.
