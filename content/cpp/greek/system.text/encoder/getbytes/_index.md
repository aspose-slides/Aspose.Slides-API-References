---
title: GetBytes()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λάβετε τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer.
type: docs
weight: 53
url: /el/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) μέθοδος

Λάβετε τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Χαρακτήρες προς κωδικοποίηση. |
| charIndex | int | Offset του πηγαίου πίνακα. |
| charCount | int | Μήκος υποπίνακα πηγής. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer προορισμού byte. |
| byteIndex | int | Offset buffer προορισμού. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του encoder μετά τον υπολογισμό. |

### Τιμή Επιστροφής

Αριθμός των bytes που γράφτηκε.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) μέθοδος

Λάβετε τα bytes που προκύπτουν από την κωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const char_t * | Χαρακτήρες προς κωδικοποίηση. |
| charCount | int | Μήκος πηγαίου πίνακα. |
| bytes | **uint8_t** * | Buffer προορισμού byte. |
| byteCount | int | Μέγεθος buffer προορισμού. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του encoder μετά τον υπολογισμό. |

### Τιμή Επιστροφής

Αριθμός των bytes που γράφτηκε.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Encoder](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)