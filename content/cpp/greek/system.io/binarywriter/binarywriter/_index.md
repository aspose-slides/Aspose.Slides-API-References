---
title: BinaryWriter()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα παράδειγμα της κλάσης BinaryWriter που γράφει δεδομένα στο καθορισμένο ρεύμα χρησιμοποιώντας την καθορισμένη κωδικοποίηση.
type: docs
weight: 1
url: /el/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) Κατασκευαστής

Δημιουργεί ένα παράδειγμα της κλάσης [BinaryWriter](../) που γράφει δεδομένα στο καθορισμένο ρεύμα χρησιμοποιώντας την καθορισμένη κωδικοποίηση.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Το ρεύμα εξόδου |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση που θα χρησιμοποιηθεί |
| leaveopen | **bool** | Καθορίζει εάν το **stream** πρέπει να παραμείνει ανοιχτό (true) μετά την αποδέσμευση του τρέχοντος αντικειμένου ή όχι (false) |

## Δείτε επίσης

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Κλάση [BinaryWriter](../)
* Χώρος ονομάτων [System::IO](../../)
* Library [Aspose.Slides](../../../)