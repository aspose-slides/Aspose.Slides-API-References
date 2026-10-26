---
title: Convert()
second_title: Aspose.Slides για C++ API αναφορά
description: Μετατρέπει bytes μεταξύ δύο κωδικοποιήσεων.
type: docs
weight: 378
url: /el/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) μέθοδος


Μετατρέπει bytes μεταξύ δύο κωδικοποιήσεων.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Κωδικοποίηση προέλευσης. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Κωδικοποίηση προορισμού. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytes προς μετατροπή. |

### Επιστρεφόμενη τιμή

Μετατρεπόμενα bytes.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) μέθοδος


Μετατρέπει bytes μεταξύ δύο κωδικοποιήσεων.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Κωδικοποίηση προέλευσης. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Κωδικοποίηση προορισμού. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytes προς μετατροπή. |
| index | int | Αρχή του τμήματος. |
| count | int | Μέγεθος τμήματος. |

### Επιστρεφόμενη τιμή

Μετατρεπόμενα bytes.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Κλάση [Encoding](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)