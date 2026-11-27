# Weekmenu

Weekmenu voor het gezin (vrijdag t/m donderdag): per dag het gerecht, en per gezinslid of hij of zij thuis eet, later komt of niet mee-eet.

- Statische pagina op GitHub Pages; gedeelde gegevens in Firebase Firestore.
- Toegang via een link met een geheime gezinscode (`#code`). Zonder code is er niets te zien.
- `firestore.rules` bevat de beveiligingsregels voor Firestore (plakken in de Firebase-console onder Firestore → Rules).
- Staat `FIREBASE_CONFIG` in `index.html` op `null`, dan draait de app in proefmodus (alleen op dit apparaat).
