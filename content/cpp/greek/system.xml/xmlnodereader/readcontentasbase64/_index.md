---
title: ReadContentAsBase64()
second_title: Aspose.Slides για C++ API Αναφορά
description: Διαβάζει το περιεχόμενο και επιστρέφει τα δυαδικά bytes που έχουν αποκωδικοποιηθεί σε Base64.
type: docs
weight: 443
url: /el/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) μέθοδος

Διαβάζει το περιεχόμενο και επιστρέφει τα δυαδικά bytes που έχουν αποκωδικοποιηθεί σε Base64.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Το buffer στο οποίο θα αντιγραφεί το προκύπτον κείμενο. Αυτή η τιμή δεν μπορεί να είναι **nullptr**. |
| index | **int32_t** | Η μετατόπιση στο buffer από όπου θα αρχίσει η αντιγραφή του αποτελέσματος. |
| count | **int32_t** | Ο μέγιστος αριθμός bytes που θα αντιγραφούν στο buffer. Ο πραγματικός αριθμός των αντιγραμμένων bytes επιστρέφεται από αυτή τη μέθοδο. |

### Τιμή Επιστροφής

Ο αριθμός των bytes που γράφτηκε στο buffer.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [XmlNodeReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Library [Aspose.Slides](../../../)