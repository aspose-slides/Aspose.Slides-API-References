---
title: Convert()
second_title: Aspose.Slides για C++ API Reference
description: Μετατρέπει χαρακτήρες σε bytes.
type: docs
weight: 79
url: /el/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

Μετατρέπει χαρακτήρες σε bytes.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Χαρακτήρες προς κωδικοποίηση. |
| charIndex | int | Μετατόπιση εισαγόμενης προσωρινής μνήμης. |
| charCount | int | Μέγεθος εισαγόμενης προσωρινής μνήμης. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Διαμεσολαβητής bytes προορισμού. |
| byteIndex | int | Μετατόπιση πίνακα προορισμού. |
| byteCount | int | Μέγεθος πίνακα προορισμού. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του κωδικοποιητή μετά τον υπολογισμό. |
| charsUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του πλήθους των χαρακτήρων που διαβάστηκαν. |
| bytesUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του πλήθους των bytes που γράφτηκαν. |
| completed | **bool**\& | Αναφορά σε μεταβλητή που θα οριστεί σε true εάν η εισαγόμενη προσωρινή μνήμη εξαντλήθηκε και σε false διαφορετικά. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

Μετατρέπει χαρακτήρες σε bytes.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Χαρακτήρες προς κωδικοποίηση. |
| charCount | int | Μέγεθος εισαγόμενης προσωρινής μνήμης. |
| bytes | **uint8_t** * | Διαμεσολαβητής bytes προορισμού. |
| byteCount | int | Μέγεθος πίνακα προορισμού. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του κωδικοποιητή μετά τον υπολογισμό. |
| charsUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του πλήθους των χαρακτήρων που διαβάστηκαν. |
| bytesUsed | int\& | Αναφορά σε μεταβλητή για αποθήκευση του πλήθους των bytes που γράφτηκαν. |
| completed | **bool**\& | Αναφορά σε μεταβλητή που θα οριστεί σε true εάν η εισαγόμενη προσωρινή μνήμη εξαντλήθηκε και σε false διαφορετικά. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)