---
title: GetByteCount()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Λαμβάνει τον αριθμό των byte που απαιτούνται για την κωδικοποίηση ενός buffer.
type: docs
weight: 40
url: /el/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) μέθοδος


Παίρνει τον αριθμό των byte που απαιτούνται για την κωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Χαρακτήρες για κωδικοποίηση. |
| index | int | [Buffer](../../../system/buffer/) Μετατόπιση. |
| count | int | Αριθμός χαρακτήρων για κωδικοποίηση. |
| flush | **bool** | Εάν είναι true, καθαρίζει την εσωτερική κατάσταση του κωδικοποιητή μετά τον υπολογισμό. |

### Τιμή Επιστροφής

Αριθμός byte που απαιτούνται για την κωδικοποίηση του buffer.

## ICUEncoder::GetByteCount(const char_t *, int, bool) μέθοδος


Παίρνει τον αριθμό των byte που απαιτούνται για την κωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const char_t * | Χαρακτήρες για κωδικοποίηση. |
| count | int | Αριθμός χαρακτήρων για κωδικοποίηση. |
| flush | **bool** | Εάν είναι true, καθαρίζει την εσωτερική κατάσταση του κωδικοποιητή μετά τον υπολογισμό. |

### Τιμή Επιστροφής

Αριθμός byte που απαιτούνται για την κωδικοποίηση του buffer.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICUEncoder](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)