---
title: ReadContentAsBinHex()
second_title: Aspose.Slides για C++ Αναφορά API
description: Διαβάζει το περιεχόμενο και επιστρέφει τα δυαδικά bytes που αποκωδικοποιήθηκαν με BinHex.
type: docs
weight: 599
url: /el/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) μέθοδος


Διαβάζει το περιεχόμενο και επιστρέφει τα δυαδικά bytes που αποκωδικοποιήθηκαν με BinHex.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Το buffer στο οποίο θα αντιγραφεί το παραγόμενο κείμενο. Αυτή η τιμή δεν μπορεί να είναι **nullptr**. |
| index | **int32_t** | Η μετατόπιση στο buffer από την οποία ξεκινά η αντιγραφή του αποτελέσματος. |
| count | **int32_t** | Ο μέγιστος αριθμός bytes που θα αντιγραφούν στο buffer. Ο πραγματικός αριθμός των αντιγραμμένων bytes επιστρέφεται από αυτή τη μέθοδο. |

### Τιμή Επιστροφής

Ο αριθμός των bytes που γράφτηκαν στο buffer.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [XmlValidatingReader](../)
* Περιοχή ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)