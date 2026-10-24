# Viloyatga Boramiz — updated interactive prototype

## Run it
1. Extract the ZIP file.
2. Open `index.html` in a modern browser.
3. For geolocation, use HTTPS or localhost and allow the browser location permission.

## Included in this prototype
- Driver/passenger selection followed by role-specific sign-in form and spinning globe loading animation.
- Passenger map, browser location permission, clickable pickup point, Uzbekistan regions and district choices.
- Route distance/time estimates and a thick green route line when public map/routing services are available.
- Driver trip publishing, matching listings, up to four passenger seats, payment choice UI, and editable profile/logout confirmation.
- Driver listings saved in the same browser using local storage.

## Important limitations
- This is a front-end demo, not a deployed taxi service. Authentication is not secure and does not verify phone numbers or emails.
- Listings are stored only in this browser; they do not sync to other devices. Seeded DEMO drivers are fictional.
- Maps, geocoding, and route estimates depend on public OpenStreetMap/Nominatim/OSRM services and internet access. Availability and route accuracy are not guaranteed.
- Card payment is only a visual demo. Do not enter real card details; no payment provider is connected and the form does not submit or store card details.
- A production version needs a secure backend, database, verified driver accounts, privacy controls, and a compliant payment provider.
