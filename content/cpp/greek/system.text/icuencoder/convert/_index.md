---
title: Convert()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει χαρακτήρες σε bytes.
type: docs
weight: 66
url: /el/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) μέθοδος

Μετατρέπει χαρακτήρες σε bytes.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Χαρακτήρες για κωδικοποίηση. |
| charIndex | int | Μετατόπιση buffer εισόδου. |
| charCount | int | Μέγεθος buffer εισόδου. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer προορισμού byte. |
| byteIndex | int | Μετατόπιση πίνακα προορισμού. |
| byteCount | int | Μέγεθος πίνακα προορισμού. |
| flush | **bool** | Αν true, καθαρίζει την εσωτερική κατάσταση του κωδικοποιητή μετά τον υπολογισμό. |
| charsUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του αριθμού των χαρακτήρων που διαβλήθηκαν. |
| bytesUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του αριθμού των bytes που γράφτηκαν. |
| completed | **bool**\& | Αναφορά σε μεταβλητή που θα τεθεί σε true εάν το buffer εισόδου εξαντληθεί και σε false διαφορετικά. |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) μέθοδος

Μετατρέπει χαρακτήρες σε bytes.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const char_t * | Χαρακτήρες για κωδικοποίηση. |
| charCount | int | Μέγεθος buffer εισόδου. |
| bytes | **uint8_t** * | Buffer προορισμού byte. |
| byteCount | int | Μέγεθος πίνακα προορισμού. |
| flush | **bool** | Αν true, καθαρίζει την εσωτερική κατάσταση του κωδικοποιητή μετά τον υπολογισμό. |
| charsUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του αριθμού των χαρακτήρων που διαβλήθηκαν. |
| bytesUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του αριθμού των bytes που γράφτηκαν. |
| completed | **bool**\& | Αναφορά σε μεταβλητή που θα τεθεί σε true εάν το buffer εισόδου εξαντληθεί και σε false διαφορετικά. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICUEncoder](../)
* Χώρος ονομάτων [System::Text](../../)
* Library [Aspose.Slides](../../../)