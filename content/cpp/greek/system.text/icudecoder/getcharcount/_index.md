---
title: GetCharCount()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αποκτά τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer.
type: docs
weight: 40
url: /el/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) μέθοδος


Αποκτά τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes προς αποκωδικοποίηση. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Αριθμός bytes προς αποκωδικοποίηση. |

### Τιμή επιστροφής

Αριθμός χαρακτήρων που απαιτούνται για την αποκωδικοποίηση του buffer.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) μέθοδος


Αποκτά τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes προς αποκωδικοποίηση. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Αριθμός bytes προς αποκωδικοποίηση. |
| flush | **bool** | Εάν είναι true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |

### Τιμή επιστροφής

Αριθμός χαρακτήρων που απαιτούνται για την αποκωδικοποίηση του buffer.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) μέθοδος


Αποκτά τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes προς αποκωδικοποίηση. |
| count | int | Αριθμός bytes προς αποκωδικοποίηση. |
| flush | **bool** | Εάν είναι true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |

### Τιμή επιστροφής

Αριθμός χαρακτήρων που απαιτούνται για την αποκωδικοποίηση του buffer.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICUDecoder](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)