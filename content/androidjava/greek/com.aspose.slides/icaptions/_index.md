---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Αναπαριστά τις κλειστές υποτιτλιστικές σημάνσεις WebVTT.
type: docs
url: /el/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Αναπαριστά τις κλειστές υποτιτλιστικές σημάνσεις WebVTT.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Επιστρέφει το παγκοσμίως μοναδικό αναγνωριστικό (GUID) των κλειστών υποτίτλων. |
| [getLabel()](#getLabel--) | Επιστρέφει ή ορίζει την ετικέτα των κλειστών υποτίτλων. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Επιστρέφει ή ορίζει την ετικέτα των κλειστών υποτίτλων. |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει τα δυαδικά δεδομένα των κλειστών υποτίτλων. |
| [getDataAsString()](#getDataAsString--) | Επιστρέφει τα δεδομένα των κλειστών υποτίτλων ως συμβολοσειρά κωδικοποιημένη σε UTF-8 Μόνο για ανάγνωση String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

Επιστρέφει το παγκοσμίως μοναδικό αναγνωριστικό (GUID) των κλειστών υποτίτλων. Μόνο για ανάγνωση java.util.UUID.

**Επιστρέφει:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

Επιστρέφει ή ορίζει την ετικέτα των κλειστών υποτίτλων. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

Επιστρέφει ή ορίζει την ετικέτα των κλειστών υποτίτλων. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Επιστρέφει τα δυαδικά δεδομένα των κλειστών υποτίτλων. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

Επιστρέφει τα δεδομένα των κλειστών υποτίτλων ως συμβολοσειρά κωδικοποιημένη σε UTF-8. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String