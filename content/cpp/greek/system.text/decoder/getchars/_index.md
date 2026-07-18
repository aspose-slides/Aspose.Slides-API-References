---
title: GetChars()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer.
type: docs
weight: 53
url: /el/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) μέθοδος


Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes προς αποκωδικοποίηση. |
| byteIndex | int | Μετατόπιση buffer εισόδου. |
| byteCount | int | Μέγεθος buffer εισόδου. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Προορισμένο buffer χαρακτήρων. |
| charIndex | int | Μετατόπιση πίνακα προορισμού. |

### Τιμή επιστροφής

Αριθμός χαρακτήρων που γράφτηκαν.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) μέθοδος


Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes προς αποκωδικοποίηση. |
| byteIndex | int | Μετατόπιση buffer εισόδου. |
| byteCount | int | Μέγεθος buffer εισόδου. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Προορισμένο buffer χαρακτήρων. |
| charIndex | int | Μετατόπιση πίνακα προορισμού. |
| flush | **bool** | Αν true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |

### Τιμή επιστροφής

Αριθμός χαρακτήρων που γράφτηκαν.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) μέθοδος


Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes προς αποκωδικοποίηση. |
| byteCount | int | Μέγεθος buffer εισόδου. |
| chars | char_t * | Προορισμένο buffer χαρακτήρων. |
| charCount | int | Μέγεθος πίνακα προορισμού. |
| flush | **bool** | Αν true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |

### Τιμή επιστροφής

Αριθμός χαρακτήρων που γράφτηκαν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Decoder](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)