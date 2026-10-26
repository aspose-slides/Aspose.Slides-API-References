---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides για C++ αναφορά API
description: Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο Base64.
type: docs
weight: 586
url: /el/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο Base64.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Η εσφαλμένη μνήμη στην οποία θα αντιγραφεί το προκύπτον κείμενο. Αυτή η τιμή δεν μπορεί να είναι **nullptr**. |
| index | **int32_t** | Η μετατόπιση στην εσφαλμένη μνήμη από την οποία θα αρχίσει η αντιγραφή του αποτελέσματος. |
| count | **int32_t** | Ο μέγιστος αριθμός byte που θα αντιγραφούν στην εσφαλμένη μνήμη. Ο πραγματικός αριθμός των byte που αντιγράφηκαν επιστρέφεται από αυτή τη μέθοδο. |

### Τιμή Επιστροφής

Ο αριθμός των byte που γράφτηκαν στην εσφαλμένη μνήμη.

## Δείτε επίσης

* typedef [ArrayPtr](../../../system/arrayptr/)
* κλάση [XmlValidatingReader](../)
* χώρο ονομάτων [System::Xml](../../)
* βιβλιοθήκη [Aspose.Slides](../../../)