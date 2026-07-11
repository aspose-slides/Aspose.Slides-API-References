---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει πληροφορίες ενσωματωμένων δεδομένων για αντικείμενο OLE.
type: docs
url: /el/com.aspose.slides/oleembeddeddatainfo/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Αντιπροσωπεύει πληροφορίες ενσωματωμένων δεδομένων για αντικείμενο OLE.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Δημιουργεί νέες πληροφορίες ενσωματωμένων δεδομένων για αντικείμενο OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Δημιουργεί ένα νέο στιγμιότυπο πληροφοριών ενσωματωμένων δεδομένων για αντικείμενο OLE. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Επιστρέφει τα δεδομένα αρχείου ενός ενσωματωμένου αντικειμένου OLE Μόνο για ανάγνωση byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Επιστρέφει την επέκταση αρχείου για το τρέχον ενσωματωμένο αντικείμενο OLE Μόνο για ανάγνωση String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Δημιουργεί νέες πληροφορίες ενσωματωμένων δεδομένων για αντικείμενο OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Δημιουργεί ένα νέο στιγμιότυπο πληροφοριών ενσωματωμένων δεδομένων για αντικείμενο OLE.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| embeddedFileData | byte[] | Δεδομένα αρχείου ενός ενσωματωμένου αντικειμένου OLE byte[]. |
| embeddedFileExtension | java.lang.String | Επέκταση αρχείου για το τρέχον ενσωματωμένο αντικείμενο OLE String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Επιστρέφει τα δεδομένα αρχείου ενός ενσωματωμένου αντικειμένου OLE Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Επιστρέφει την επέκταση αρχείου για το τρέχον ενσωματωμένο αντικείμενο OLE Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String