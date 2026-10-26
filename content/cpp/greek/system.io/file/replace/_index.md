---
title: Replace()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αντικαθιστά τα περιεχόμενα ενός αρχείου με ένα άλλο και δημιουργεί αντίγραφο ασφαλείας του αντικατεστημένου αρχείου.
type: docs
weight: 339
url: /el/system.io/file/replace/
---
## File::Replace(const String&, const String&, const String&, bool) μέθοδος

Αντικαθιστά τα περιεχόμενα ενός αρχείου με ένα άλλο και δημιουργεί ένα αντίγραφο ασφαλείας του αντικατεστημένου αρχείου.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)& | Ένα όνομα του αρχείου με το οποίο θα γίνει αντικατάσταση |
| destinationFileName | const [String](../../../system/string/)& | Ένα όνομα του αρχείου που θα αντικατασταθεί |
| destinationBackupFileName | const [String](../../../system/string/)& | Ένα όνομα του αρχείου αντιγράφου ασφαλείας |
| ignoreMetadataErrors | **bool** | Καθορίζει αν τα σφάλματα συγχώνευσης από το αντικατεστημένο αρχείο στο αρχείο αντικατάστασης πρέπει να αγνοηθούν (true) ή όχι (false) |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [File](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)