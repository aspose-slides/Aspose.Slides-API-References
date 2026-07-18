---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides για το C++ API Reference
description: Καθορίζει πώς να αντιμετωπίζεται η χρονική τιμή κατά τη μετατροπή μεταξύ συμβολοσειράς και DateTime.
type: docs
weight: 781
url: /el/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

Καθορίζει πώς να αντιμετωπίζεται η χρονική τιμή κατά τη μετατροπή μεταξύ συμβολοσειράς και [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Local | 0 | Θεωρείται ως τοπική ώρα. Εάν το αντικείμενο [DateTime](../../system/datetime/) αντιπροσωπεύει ώρα Συντονισμένης Παγκόσμιας Ώρας (UTC), μετατρέπεται σε τοπική ώρα. |
| Utc | 1 | Θεωρείται ως UTC. Εάν το αντικείμενο [DateTime](../../system/datetime/) αντιπροσωπεύει τοπική ώρα, μετατρέπεται σε UTC. |
| Unspecified | 2 | Θεωρείται ως τοπική ώρα εάν ένα [DateTime](../../system/datetime/) μετατρέπεται σε συμβολοσειρά. Εάν μια συμβολοσειρά μετατρέπεται σε [DateTime](../../system/datetime/), μετατρέπεται σε τοπική ώρα εάν έχει καθοριστεί ζώνη ώρας. |
| RoundtripKind | 3 | Πληροφορίες ζώνης ώρας πρέπει να διατηρηθούν κατά τη μετατροπή. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)