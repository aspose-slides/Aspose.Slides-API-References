---
title: GetCharCount()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer.
type: docs
weight: 40
url: /el/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes προς αποκωδικοποίηση. |
| index | int | [Buffer](../../../system/buffer/) μετατόπιση. |
| count | int | Αριθμός bytes προς αποκωδικοποίηση. |

### Τιμή επιστροφής

Αριθμός χαρακτήρων που απαιτούνται για την αποκωδικοποίηση του buffer.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method

Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes προς αποκωδικοποίηση. |
| index | int | [Buffer](../../../system/buffer/) μετατόπιση. |
| count | int | Αριθμός bytes προς αποκωδικοποίηση. |
| flush | **bool** | Αν true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |

### Τιμή επιστροφής

Αριθμός χαρακτήρων που απαιτούνται για την αποκωδικοποίηση του buffer.

## Decoder::GetCharCount(const uint8_t *, int, bool) method

Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes προς αποκωδικοποίηση. |
| count | int | Αριθμός bytes προς αποκωδικοποίηση. |
| flush | **bool** | Αν true, καθαρίζει την εσωτερική κατάσταση του αποκωδικοποιητή μετά τον υπολογισμό. |

### Τιμή επιστροφής

Αριθμός χαρακτήρων που απαιτούνται για την αποκωδικοποίηση του buffer.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Decoder](../)
* Χώρος ονομάτων [System::Text](../../)
* Library [Aspose.Slides](../../../)