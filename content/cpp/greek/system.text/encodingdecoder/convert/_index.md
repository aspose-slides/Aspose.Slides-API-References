---
title: Convert()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει τα bytes σε χαρακτήρες.
type: docs
weight: 1
url: /el/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int&, int&, bool&) method


Μετατρέπει τα bytes σε χαρακτήρες.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes προς αποκωδικοποίηση. |
| byteCount | int | Μέγεθος του buffer εισόδου. |
| chars | char_t * | Προορισμός buffer χαρακτήρων. |
| charCount | int | Μέγεθος του πίνακα προορισμού. |
| flush | **bool** | Εάν είναι true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |
| bytesUsed | int& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των αναγνωσμένων bytes. |
| charsUsed | int& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των γραμμένων χαρακτήρων. |
| completed | **bool**& | Αναφορά σε μεταβλητή που θα τεθεί σε true εάν εξαντληθεί το buffer εισόδου και σε false διαφορετικά. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int&, int&, bool&) method


Μετατρέπει τα bytes σε χαρακτήρες.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes προς αποκωδικοποίηση. |
| byteIndex | int | Μετατόπιση του buffer εισόδου. |
| byteCount | int | Μέγεθος του buffer εισόδου. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Προορισμός buffer χαρακτήρων. |
| charIndex | int | Μετατόπιση του πίνακα προορισμού. |
| charCount | int | Μέγεθος του πίνακα προορισμού. |
| flush | **bool** | Εάν είναι true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |
| bytesUsed | int& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των αναγνωσμένων bytes. |
| charsUsed | int& | Αναφορά σε μεταβλητή για την αποθήκευση του αριθμού των γραμμένων χαρακτήρων. |
| completed | **bool**& | Αναφορά σε μεταβλητή που θα τεθεί σε true εάν εξαντληθεί το buffer εισόδου και σε false διαφορετικά. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [EncodingDecoder](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)