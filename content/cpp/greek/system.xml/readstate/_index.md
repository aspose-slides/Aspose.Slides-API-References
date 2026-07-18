---
title: ReadState
second_title: Aspose.Slides για C++ - Αναφορά API
description: Καθορίζει την κατάσταση του αναγνώστη.
type: docs
weight: 703
url: /el/system.xml/readstate/
---
## ReadState enum


Καθορίζει την κατάσταση του αναγνώστη.

```cpp
enum class ReadState
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Initial | 0 | Η μέθοδος [XmlReader::Read](../xmlreader/read/) δεν έχει κληθεί. |
| Interactive | 1 | Η μέθοδος [XmlReader::Read](../xmlreader/read/) έχει κληθεί. Επιπλέον μέθοδοι μπορεί να κληθούν στον αναγνώστη. |
| Error | 2 | Παρουσιάστηκε σφάλμα που εμποδίζει τη συνέχιση της λειτουργίας ανάγνωσης. |
| EndOfFile | 3 | Το τέλος του αρχείου έχει επιτευχθεί επιτυχώς. |
| Closed | 4 | Η μέθοδος [XmlReader::Close](../xmlreader/close/) έχει κληθεί. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)