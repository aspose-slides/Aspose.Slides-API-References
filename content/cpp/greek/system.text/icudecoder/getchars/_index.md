---
title: GetChars()
second_title: Αναφορά API Aspose.Slides για C++
description: Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer.
type: docs
weight: 53
url: /el/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes προς αποκωδικοποίηση. |
| byteIndex | int | Μετατόπιση εισαγωγικού buffer. |
| byteCount | int | Μέγεθος εισαγωγικού buffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Προορισμιας buffer χαρακτήρων. |
| charIndex | int | Μετατόπιση προορισμιού array. |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων που γράφτηκαν.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes προς αποκωδικοποίηση. |
| byteIndex | int | Μετατόπιση εισαγωγικού buffer. |
| byteCount | int | Μέγεθος εισαγωγικού buffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Προορισμιας buffer χαρακτήρων. |
| charIndex | int | Μετατόπιση προορισμιού array. |
| flush | **bool** | Εάν είναι true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων που γράφτηκαν.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) method

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes προς αποκωδικοποίηση. |
| byteCount | int | Μέγεθος εισαγωγικού buffer. |
| chars | char_t * | Προορισμιας buffer χαρακτήρων. |
| charCount | int | Μέγεθος προορισμιού array. |
| flush | **bool** | Εάν είναι true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων που γράφτηκαν.

## Δείτε επίσης

* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICUDecoder](../)
* Ονοματικόχώρο [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)