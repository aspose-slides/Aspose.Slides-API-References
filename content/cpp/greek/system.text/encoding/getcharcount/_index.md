---
title: GetCharCount()
second_title: Αναφορά API Aspose.Slides για C++
description: Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός byte buffer.
type: docs
weight: 261
url: /el/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) μέθοδος

Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes για αποκωδικοποίηση. |
| index | int | Αρχή του slice. |
| count | int | Μέγεθος του slice. |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων.

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) μέθοδος

Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes για αποκωδικοποίηση. |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων.

## Encoding::GetCharCount(const uint8_t *, int) μέθοδος

Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes για αποκωδικοποίηση. |
| count | int | Αριθμός bytes. |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Encoding](../)
* Χώρος ονομάτων [System::Text](../../)
* Library [Aspose.Slides](../../../)