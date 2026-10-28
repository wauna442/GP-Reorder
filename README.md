# GP-Reorder — GenPac Re-Order

Mobile web app for building re-order lists:

1. Scan an item barcode (or type the Item ID) and confirm it
2. Enter a quantity
3. Pick a unit: Each, Box, Reel, or a custom unit
4. Add the line to the order, then scan the next item or e-mail the order

E-Mail order opens the phone's share sheet with the order as a `.csv` attachment and as text in the body.

## Hosting
Turn on **Settings → Pages** (branch `main`, folder `/root`). Open the Pages URL on a phone, allow camera access, and choose **Add to Home Screen**. The camera requires HTTPS, which GitHub Pages provides.
