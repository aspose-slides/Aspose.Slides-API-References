---
title: GetByteCount()
second_title: Aspose.Slides για την Αναφορά API C++
description: Επιστρέφει τον αριθμό των byte που απαιτούνται για την κωδικοποίηση ενός buffer.
type: docs
weight: 40
url: /el/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) μέθοδος

Επιστρέφει τον αριθμό των byte που χρειάζονται για την κωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Χαρακτήρες προς κωδικοποίηση. |
| index | int | [Buffer](../../../system/buffer/) μετατόπιση. |
| count | int | Αριθμός χαρακτήρων προς κωδικοποίηση. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του κωδικοποιητή μετά τον υπολογισμό. |

### Τιμή Επιστροφής

Αριθμός byte που απαιτείται για την κωδικοποίηση του buffer.

## Encoder::GetByteCount(const char_t *, int, bool) μέθοδος

Επιστρέφει τον αριθμό των byte που χρειάζονται για την κωδικοποίηση ενός buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const char_t * | Χαρακτήρες προς κωδικοποίηση. |
| count | int | Αριθμός χαρακτήρων προς κωδικοποίηση. |
| flush | **bool** | Αν είναι true, καθαρίζει την εσωτερική κατάσταση του κωδικοποιητή μετά τον υπολογισμό. |

### Τιμή Επιστροφής

Αριθμός byte που απαιτείται για την κωδικοποίηση του buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Encoder](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)