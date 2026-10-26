---
title: ReadContentAsBase64()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αναγνώνει το περιεχόμενο και επιστρέφει τα δυαδικά bytes που αποκωδικοποιήθηκαν από Base64.
type: docs
weight: 638
url: /el/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

Αναγνώνει το περιεχόμενο και επιστρέφει τα **Base64** αποκωδικοποιημένα δυαδικά bytes.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Το buffer στο οποίο αντιγράφεται το παραγόμενο κείμενο. Αυτή η τιμή δεν μπορεί να είναι **nullptr**. |
| index | **int32_t** | Η μετατόπιση μέσα στο buffer από την οποία ξεκινά η αντιγραφή του αποτελέσματος. |
| count | **int32_t** | Ο μέγιστος αριθμός bytes που θα αντιγραφούν στο buffer. Ο πραγματικός αριθμός των αντιγραμμένων bytes επιστρέφεται από αυτή τη μέθοδο. |

### Τιμή Επιστροφής

Ο αριθμός των bytes που γράφτηκαν στο buffer.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [XmlTextReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)