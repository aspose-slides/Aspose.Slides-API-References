---
title: Convert()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Μετατρέπει bytes σε χαρακτήρες.
type: docs
weight: 79
url: /el/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Μετατρέπει bytes σε χαρακτήρες.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes για αποκωδικοποίηση. |
| byteIndex | int | Μετατόπιση του εισαγωγικού buffer. |
| byteCount | int | Μέγεθος του εισαγωγικού buffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer προορισμού χαρακτήρων. |
| charIndex | int | Μετατόπιση του πίνακα προορισμού. |
| charCount | int | Μέγεθος του πίνακα προορισμού. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |
| bytesUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του πλήθους των αναγνωσμένων bytes. |
| charsUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του πλήθους των γραμμένων χαρακτήρων. |
| completed | **bool**\& | Αναφορά σε μεταβλητή που θα οριστεί σε true αν το εισαγωγικό buffer εξαντληθεί, και σε false διαφορετικά. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Μετατρέπει bytes σε χαρακτήρες.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes για αποκωδικοποίηση. |
| byteCount | int | Μέγεθος του εισαγωγικού buffer. |
| chars | char_t * | Buffer προορισμού χαρακτήρων. |
| charCount | int | Μέγεθος του πίνακα προορισμού. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |
| bytesUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του πλήθους των αναγνωσμένων bytes. |
| charsUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του πλήθους των γραμμένων χαρακτήρων. |
| completed | **bool**\& | Αναφορά σε μεταβλητή που θα οριστεί σε true αν το εισαγωγικό buffer εξαντληθεί, και σε false διαφορετικά. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)