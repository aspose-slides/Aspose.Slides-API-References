---
title: Convert()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει τα byte σε χαρακτήρες.
type: docs
weight: 66
url: /el/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method

Μετατρέπει τα byte σε χαρακτήρες.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte προς αποκωδικοποίηση. |
| byteIndex | int | Μετατόπιση του input buffer. |
| byteCount | int | Μέγεθος του input buffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Προορισ buffer χαρακτήρων. |
| charIndex | int | Μετατόπιση του προοριστικού array. |
| charCount | int | Μέγεθος του προοριστικού array. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |
| bytesUsed | int\& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των byte που διαβάστηκαν. |
| charsUsed | int\& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των χαρακτήρων που γράφτηκαν. |
| completed | **bool**\& | Αναφορά σε μεταβλητή που θα οριστεί σε true αν το input buffer εξαντλήθηκε και σε false διαφορετικά. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method

Μετατρέπει τα byte σε χαρακτήρες.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte προς αποκωδικοποίηση. |
| byteCount | int | Μέγεθος του input buffer. |
| chars | char_t * | Προορισ buffer χαρακτήρων. |
| charCount | int | Μέγεθος του προοριστικού array. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |
| bytesUsed | int\& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των byte που διαβάστηκαν. |
| charsUsed | int\& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των χαρακτήρων που γράφτηκαν. |
| completed | **bool**\& | Αναφορά σε μεταβλητή που θα οριστεί σε true αν το input buffer εξαντλήθηκε και σε false διαφορετικά. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICUDecoder](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)