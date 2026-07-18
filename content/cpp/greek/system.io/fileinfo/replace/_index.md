---
title: Replace()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντικαθιστά τα περιεχόμενα ενός καθορισμένου αρχείου προορισμού με το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο FileInfo και δημιουργεί αντίγραφο ασφαλείας του αντικατεστημένου αρχείου.
type: docs
weight: 131
url: /el/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) μέθοδος


Αντικαθιστά τα περιεχόμενα ενός καθορισμένου αρχείου προορισμού με το αρχείο που αντιπροσωπεύεται από το τρέχον [FileInfo](../) αντικείμενο και δημιουργεί αντίγραφο ασφαλείας του αντικατεστημένου αρχείου.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Ένα όνομα του αρχείου προς αντικατάσταση |
| destinationBackupFileName | const [String](../../../system/string/)\& | Ένα όνομα του αρχείου αντιγράφου ασφαλείας |

### Τιμή επιστροφής

Ένα αντικείμενο FileInfor που αντιπροσωπεύει το αρχείο στο οποίο δείχνει **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) μέθοδος


Αντικαθιστά τα περιεχόμενα ενός καθορισμένου αρχείου προορισμού με το αρχείο που αντιπροσωπεύεται από το τρέχον [FileInfo](../) αντικείμενο και δημιουργεί αντίγραφο ασφαλείας του αντικατεστημένου αρχείου.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Ένα όνομα του αρχείου προς αντικατάσταση |
| destinationBackupFileName | const [String](../../../system/string/)\& | Ένα όνομα του αρχείου αντιγράφου ασφαλείας |
| ignoreMetadataErrors | **bool** | Καθορίζει αν τα σφάλματα συγχώνευσης από το αντικατεστημένο αρχείο στο αρχείο αντικατάστασης θα πρέπει να αγνοηθούν (true) ή όχι (false) |

### Τιμή επιστροφής

Ένα αντικείμενο FileInfor που αντιπροσωπεύει το αρχείο στο οποίο δείχνει **destinationFileName**

## Δείτε επίσης

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [FileInfo](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)