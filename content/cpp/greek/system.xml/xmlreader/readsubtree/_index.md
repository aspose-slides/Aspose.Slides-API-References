---
title: ReadSubtree()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει ένα νέο αντικείμενο XmlReader που μπορεί να χρησιμοποιηθεί για την ανάγνωση του τρέχοντος κόμβου και όλων των απογόνων του.
type: docs
weight: 963
url: /el/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() μέθοδος


Επιστρέφει ένα νέο [XmlReader](../) αντικείμενο που μπορεί να χρησιμοποιηθεί για την ανάγνωση του τρέχοντος κόμβου και όλων των απογόνων του.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```


### Τιμή επιστροφής

Ένα νέο αντικείμενο αναγνώστη XML ορισμένο στο [ReadState::Initial](../../readstate/). Η κλήση της [XmlReader::Read](../read/) μεθόδου τοποθετεί το νέο αναγνώστη στον κόμβο που ήταν τρέχων πριν από την κλήση της [XmlReader::ReadSubtree](./) μεθόδου.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)