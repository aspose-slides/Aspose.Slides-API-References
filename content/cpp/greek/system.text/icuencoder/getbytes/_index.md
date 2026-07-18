---
title: GetBytes()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λάβετε τα byte που προκύπτουν από την κωδικοποίηση ενός buffer.
type: docs
weight: 53
url: /el/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) μέθοδος

Λάβετε τα byte που προκύπτουν από την κωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Χαρακτήρες για κωδικοποίηση. |
| charIndex | int | Μετατόπιση array προέλευσης. |
| charCount | int | Μήκος υπο-παραγόμενου array προέλευσης. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Προορισμός buffer byte. |
| byteIndex | int | Μετατόπιση buffer προορισμού. |
| flush | **bool** | Εάν είναι true, καθαρίζει την εσωτερική κατάσταση κωδικοποιητή μετά τον υπολογισμό. |

### Τιμή Επιστροφής

Αριθμός byte που γράφτηκαν.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) μέθοδος

Λάβετε τα byte που προκύπτουν από την κωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const char_t * | Χαρακτήρες για κωδικοποίηση. |
| charCount | int | Μήκος array προέλευσης. |
| bytes | **uint8_t** * | Προορισμός buffer byte. |
| byteCount | int | Μέγεθος buffer προορισμού. |
| flush | **bool** | Εάν είναι true, καθαρίζει την εσωτερική κατάσταση κωδικοποιητή μετά τον υπολογισμό. |

### Τιμή Επιστροφής

Αριθμός byte που γράφτηκαν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)