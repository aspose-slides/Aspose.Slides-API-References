---
title: GetCharCount()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Παίρνει τον αριθμό των χαρακτήρων που χρειάζονται για την αποκωδικοποίηση ενός buffer byte.
type: docs
weight: 53
url: /el/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) μέθοδος


Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer bytes.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) μέθοδος


Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) μέθοδος


Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων.

## ICUEncoding::GetCharCount(const uint8_t *, int) μέθοδος


Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την αποκωδικοποίηση ενός buffer bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICUEncoding](../)
* Χώρος ονομάτων [System::Text](../../)
* Library [Aspose.Slides](../../../)