---
title: Convert()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει χαρακτήρες σε bytes.
type: docs
weight: 1
url: /el/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method


Μετατρέπει χαρακτήρες σε bytes.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Χαρακτήρες για κωδικοποίηση. |
| charCount | int | Μέγεθος εισαγωγικού buffer. |
| bytes | **uint8_t** * | Προορισμός byte buffer. |
| byteCount | int | Μέγεθος προορισμού του πίνακα. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του κωδικοποιητή μετά τον υπολογισμό. |
| charsUsed | int\& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των χαρακτήρων που διαβάστηκαν. |
| bytesUsed | int\& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των bytes που γράφτηκαν. |
| completed | **bool**\& | Αναφορά σε μεταβλητή που θα οριστεί σε true εάν το buffer εισόδου εξαντληθεί και σε false διαφορετικά. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method


Μετατρέπει χαρακτήρες σε bytes.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Χαρακτήρες για κωδικοποίηση. |
| charIndex | int | Μετατόπιση εισαγωγικού buffer. |
| charCount | int | Μέγεθος εισαγωγικού buffer. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Προορισμός byte buffer. |
| byteIndex | int | Μετατόπιση προορισμού του πίνακα. |
| byteCount | int | Μέγεθος προορισμού του πίνακα. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του κωδικοποιητή μετά τον υπολογισμό. |
| charsUsed | int\& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των χαρακτήρων που διαβάστηκαν. |
| bytesUsed | int\& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των bytes που γράφτηκαν. |
| completed | **bool**\& | Αναφορά σε μεταβλητή που θα οριστεί σε true εάν το buffer εισόδου εξαντληθεί και σε false διαφορετικά. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [EncodingEncoder](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)