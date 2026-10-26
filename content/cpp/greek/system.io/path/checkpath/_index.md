---
title: CheckPath()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει εάν το καθορισμένο μονοπάτι είναι έγκυρο ελέγχοντας αν περιέχει μη έγκυρους χαρακτήρες. Εξαίρεση εκτοξεύεται εάν το μονοπάτι περιέχει μη έγκυρους χαρακτήρες.
type: docs
weight: 209
url: /el/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) μέθοδος

Καθορίζει εάν το συγκεκριμένο μονοπάτι είναι έγκυρο ελέγχοντας αν περιέχει μη έγκυρους χαρακτήρες. Εξαίρεση εκτοξεύεται εάν το μονοπάτι περιέχει μη έγκυρους χαρακτήρες.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Το path προς έλεγχο |
| msg | const [String](../../../system/string/)\& | Το msg προς μεταβίβαση στον κατασκευαστή του αντικειμένου εξαίρεσης |
| allow_empty | **bool** | Καθορίζει εάν μια κενή ή null συμβολοσειρά πρέπει να θεωρείται σωστό μονοπάτι (true) ή όχι (false); εάν αυτή η παράμετρος είναι false και **path** είναι κενό, ρίχνεται ArgumentException· εάν αυτή η παράμετρος είναι false και **path** είναι null, ρίχνεται ArgumentNullException |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [Path](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)