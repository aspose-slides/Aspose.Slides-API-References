---
title: Captions
second_title: Aspose.Slides για Java Αναφορά API
description: Αντιπροσωπεύει τους κλειστούς υπότιτλους WebVTT.
type: docs
url: /el/com.aspose.slides/captions/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

Αντιπροσωπεύει τα κλειστά υπότιτλους WebVTT.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Επιστρέφει το παγκοσμίως μοναδικό αναγνωριστικό (GUID) των κλειστών υποτίτλων. |
| [getLabel()](#getLabel--) | Επιστρέφει ή ορίζει την ετικέτα των κλειστών υποτίτλων. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Επιστρέφει ή ορίζει την ετικέτα των κλειστών υποτίτλων. |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει τα δυαδικά δεδομένα των κλειστών υποτίτλων. |
| [getDataAsString()](#getDataAsString--) | Επιστρέφει τα δεδομένα των κλειστών υποτίτλων ως συμβολοσειρά κωδικοποιημένη σε UTF-8 Μόνο ανάγνωση String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


Επιστρέφει το παγκοσμίως μοναδικό αναγνωριστικό (GUID) των κλειστών υποτίτλων. Μόνο ανάγνωση java.util.UUID.

**Επιστρέφει:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


Επιστρέφει ή ορίζει την ετικέτα των κλειστών υποτίτλων. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


Επιστρέφει ή ορίζει την ετικέτα των κλειστών υποτίτλων. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Επιστρέφει τα δυαδικά δεδομένα των κλειστών υποτίτλων. Μόνο ανάγνωση  byte[] .

**Επιστρέφει:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


Επιστρέφει τα δεδομένα των κλειστών υποτίτλων ως συμβολοσειρά κωδικοποιημένη σε UTF-8 Μόνο ανάγνωση String.

**Επιστρέφει:**
java.lang.String