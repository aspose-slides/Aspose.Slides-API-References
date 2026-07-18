---
title: ReadContentAsBinHex()
second_title: Αναφορά API Aspose.Slides για C++
description: Διαβάζει το περιεχόμενο και επιστρέφει τα δυαδικά byte που αποκωδικοποιήθηκαν με BinHex.
type: docs
weight: 781
url: /el/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) μέθοδος

Διαβάζει το περιεχόμενο και επιστρέφει τα **BinHex** αποκωδικοποιημένα δυαδικά byte.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Η ενδιάμεση μνήμη στην οποία θα αντιγραφεί το προκύπτον κείμενο. Αυτή η τιμή δεν μπορεί να είναι **nullptr**. |
| index | **int32_t** | Η μετατόπιση στην ενδιάμεση μνήμη από την οποία ξεκινά η αντιγραφή του αποτελέσματος. |
| count | **int32_t** | Ο μέγιστος αριθμός byte που θα αντιγραφούν στην ενδιάμεση μνήμη. Ο πραγματικός αριθμός των αντιγραμμένων byte επιστρέφεται από αυτή τη μέθοδο. |

### Τιμή επιστροφής

Ο αριθμός των byte που γράφτηκαν στην ενδιάμεση μνήμη.

## Δείτε επίσης

* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)