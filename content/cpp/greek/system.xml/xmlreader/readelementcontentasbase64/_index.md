---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides για το API C++
description: Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο Base64.
type: docs
weight: 768
url: /el/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) μέθοδος


Διαβάζει το στοιχείο και αποκωδικοποιεί το **Base64** περιεχόμενο.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Το buffer στο οποίο θα αντιγραφεί το προκύπτων κείμενο. Αυτή η τιμή δεν μπορεί να είναι **nullptr**. |
| index | **int32_t** | Η μετατόπιση στο buffer από όπου ξεκινά η αντιγραφή του αποτελέσματος. |
| count | **int32_t** | Ο μέγιστος αριθμός bytes που θα αντιγραφεί στο buffer. Ο πραγματικός αριθμός των αντιγραμμένων bytes επιστρέφεται από αυτή τη μέθοδο. |

### Τιμή Επιστροφής

Ο αριθμός των bytes που γράφτηκαν στο buffer.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)