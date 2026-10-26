---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides για C++ Αναφορά API
description: Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο Base64.
type: docs
weight: 651
url: /el/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) μέθοδος

Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο Base64.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Το buffer στο οποίο θα αντιγραφεί το προκύπτον κείμενο. Αυτή η τιμή δεν μπορεί να είναι **nullptr**. |
| index | **int32_t** | Η μετατόπιση στο buffer όπου θα ξεκινήσει η αντιγραφή του αποτελέσματος. |
| count | **int32_t** | Ο μέγιστος αριθμός byte που θα αντιγραφούν στο buffer. Ο πραγματικός αριθμός των αντιγραμμένων byte επιστρέφεται από αυτή τη μέθοδο. |

### Τιμή επιστροφής

Ο αριθμός των byte που γράφτηκαν στο buffer.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [XmlTextReader](../)
* Περιοχή ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)