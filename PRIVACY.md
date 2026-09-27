# Privacy Policy — UV Index

_Effective 23 September 2026_

UV Index ("the app") is a home-screen widget that shows the ultraviolet (UV)
index forecast for where you are. It is published by **Parasol**
("we", "us"). This policy explains what the app does with your information.

**The short version:** the app uses your approximate location to look up a UV
forecast. That location is rounded to about 1 km and sent to the forecast
service, and it's kept on your phone so the widget can refresh. We don't run a
server, we don't have accounts, and we never see, store, sell or share your data.
There are no ads, analytics or tracking.

## What the app uses

### Approximate location

With your permission, the app reads your **approximate** location (Android's
"approximate location" permission, accurate only to within a few kilometres). It doesn't ask
for precise location or background location, so it can only read your location
while the app is open on screen.

The location is used to:

1. **Fetch the forecast.** Before anything leaves your phone, the coordinates
   are rounded to two decimal places (about 1 km). They are then sent over HTTPS
   to [Open-Meteo](https://open-meteo.com), the free weather service that
   provides the UV forecast. Open-Meteo's handling of that request is covered by
   its own [terms and privacy policy](https://open-meteo.com/en/terms).
2. **Show a place name.** The app asks Android's built-in geocoding service to
   turn the location into a town or city name (for example "Lisbon"). On most
   phones this service is provided by Google as part of Android, under
   [Google's privacy policy](https://policies.google.com/privacy).

### Data kept on your phone

To let the widget refresh and redraw while the app is closed, the app saves
these on your phone:

- the last location it read, and the place name
- the most recent UV forecast and when it was fetched
- which view you picked for each small widget ("UV now" or "Today's high")
- whether clear-sky mode is on, for the app and for each widget
- the last error message, if a refresh failed

This data never leaves your phone except as described above, and it's excluded
from Android cloud backups and device-to-device transfers.

## What the app doesn't do

- It has no accounts, and doesn't ask for your name, email or any other
  personal details.
- It doesn't include advertising, analytics, crash reporting or tracking
  software.
- It doesn't send your data to us. We don't operate any servers for the app.
- It doesn't sell or share your data with anyone.

## Network requests and IP addresses

Like any internet request, a forecast request exposes your phone's IP address to
Open-Meteo, and a place-name lookup may expose it to your phone's geocoding
provider. We don't receive or control this information.

## Your choices

- **Turn off location:** in **Settings → Apps → UV Index → Permissions →
  Location**, choose "Don't allow". The widget will stop updating its location.
- **Delete the saved data:** in **Settings → Apps → UV Index → Storage**, tap
  **Clear storage**, or uninstall the app. Because the data only exists on your
  phone, that removes it completely.

## Children

The app isn't directed at children under 13 and doesn't knowingly collect
personal information from anyone.

## Changes

If this policy changes, the updated version will be published at the same
address with a new effective date. If the app ever starts handling data in a new
way, the policy will be updated before that version is released.

## Contact

Questions about this policy: **parasoldevelop@gmail.com**
