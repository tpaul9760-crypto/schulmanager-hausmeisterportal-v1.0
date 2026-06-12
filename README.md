# SchulManager v1.8.1 Cloud-Räume Fix

## Korrektur
- Räume konnten auf manchen Geräten nicht aus Firebase geladen werden.
- Die Firestore-Abfrage mit `orderBy("kategorie"), orderBy("name")` wurde entfernt.
- Dadurch ist kein Composite Index mehr nötig.
- Räume werden weiterhin über Firebase synchronisiert.
