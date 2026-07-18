---
title: WriteState
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει την κατάσταση του XmlWriter.
type: docs
weight: 755
url: /el/system.xml/writestate/
---
## WriteState enum

Καθορίζει την κατάσταση του [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Values

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Start | 0 | Δείχνει ότι η μέθοδος XmlWriter::Write δεν έχει ακόμη κληθεί. |
| Prolog | 1 | Δείχνει ότι γράφεται το προοίμιο. |
| Element | 2 | Δείχνει ότι γράφεται η ετικέτα έναρξης ενός στοιχείου. |
| Attribute | 3 | Δείχνει ότι γράφεται μια τιμή ιδιότητας. |
| Content | 4 | Δείχνει ότι γράφεται το περιεχόμενο του στοιχείου. |
| Closed | 5 | Δείχνει ότι η μέθοδος [XmlWriter::Close](../xmlwriter/close/) έχει κληθεί. |
| Error | 6 | Μια εξαίρεση έχει ριχτεί, η οποία έχει αφήσει το [XmlWriter](../xmlwriter/) σε μη έγκυρη κατάσταση. Μπορείτε να καλέσετε τη μέθοδο [XmlWriter::Close](../xmlwriter/close/) για να θέσετε το [XmlWriter](../xmlwriter/) στην κατάσταση [WriteState::Closed](./). Οποιεσδήποτε άλλες κλήσεις μεθόδου [XmlWriter](../xmlwriter/) έχουν ως αποτέλεσμα μια InvalidOperationException. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)