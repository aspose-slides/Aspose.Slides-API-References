---
title: ReadElementContentAsBinHex()
second_title: Αναφορά API Aspose.Slides για C++
description: Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο BinHex.
type: docs
weight: 482
url: /el/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) μέθοδος


Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο buffer στον οποίο θα αντιγραφεί το κείμενο αποτελέσματος. Αυτή η τιμή δεν μπορεί να είναι **nullptr**. |
| index | **int32_t** | Η μετατόπιση στο buffer όπου θα ξεκινήσει η αντιγραφή του αποτελέσματος. |
| count | **int32_t** | Ο μέγιστος αριθμός bytes προς αντιγραφή στο buffer. Ο πραγματικός αριθμός των bytes που αντιγράφηκαν επιστρέφεται από αυτήν τη μέθοδο. |

### Τιμή Επιστροφής

Ο αριθμός των bytes που γράφτηκαν στο buffer.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [XmlNodeReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)