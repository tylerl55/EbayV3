# My Inventory

A simple app for keeping track of the things you sell on eBay: what you have, where it is stored, what you paid, and how much profit you made when it sold.

It runs in a web browser. There is nothing to install and no account to create.

## Using the app

**Add something to sell**

1. Tap **Add** at the bottom of the screen.
2. Tap **Add a photo** to take a picture (optional).
3. Type a name, how many you have, and what you paid.
4. Tap **Save Item**.

**When you list it on eBay**

1. Tap **Items**, then tap the item.
2. Turn on **Listed on eBay**.

**When it sells**

1. Tap **Items**, then tap the item.
2. Tap **Mark as Sold**.
3. Type what it sold for and what you paid for shipping. The eBay fee is estimated for you, and you can change it.
4. Tap **Save Sale**. The profit is added to the **Sales** page.

**Fix a mistake**

- To change an item, open it and tap **Edit**.
- To cancel a sale, tap **Sales**, tap the sale, then tap **Undo this sale**.

## Put it on the iPhone Home Screen

1. Open the app's link in **Safari**.
2. Tap the **Share** button (the square with an arrow pointing up).
3. Scroll down and tap **Add to Home Screen**, then **Add**.

From then on, open the app from its icon. It works without internet, and the phone will not clear the list.

## Keep your list safe

Your list is stored **only on the device you use**. It is not sent anywhere, and nobody else can see it.

That also means it can be lost if the phone is lost or replaced, or if Safari's website data is cleared. To protect it:

1. Tap **More**, then **Save a backup**.
2. Choose **Save to Files** (iCloud Drive is a good place).
3. Do this every week or two. The app reminds you.

To get the list back on a new phone, open the app, tap **More**, then **Restore from a backup**, and choose the backup file.

## Spreadsheets

Under **More** you can:

- **Export items** or **Export sales** as CSV files, which open in Excel or Google Sheets.
- **Import items** from a CSV file to add many items at once. Tap **Get the import template** for an example file with the right columns. Importing adds items; it never removes what is already there. Photos are not part of CSV files.

## Settings

Under **More**:

- **eBay fee estimate (%)**: the percentage used to fill in the fee when you mark something as sold. It starts at 13.25%. eBay's real fee depends on the category, so adjust it to match what you usually see.
- **Low stock warning**: shows a "Low stock" label when an item you had several of drops to this number or less.

## For the person who hosts this

The app is a plain static website (HTML, CSS and JavaScript, no build step). To publish it with GitHub Pages:

1. Push this folder to a public GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
4. After a minute or two the app is live at `https://<username>.github.io/<repository-name>/`.

To try it on a computer first, serve the folder with any static web server and open it in a browser.
