---
title: GetChars()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.
type: docs
weight: 66
url: /el/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |
| byte_count | int | Input buffer size. |
| chars | char_t * | [Buffer](../../../system/buffer/) για τοποθέτηση χαρακτήρων. |
| char_count | int | Output buffer size. |

### Τιμή επιστροφής

Αριθμός γραμμένων χαρακτήρων.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |
| byte_index | int | Input buffer offset. |
| byte_count | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) για τοποθέτηση χαρακτήρων. |
| char_index | int | Output buffer offset. |

### Τιμή επιστροφής

Αριθμός γραμμένων χαρακτήρων.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Τιμή επιστροφής

[Buffer](../../../system/buffer/) από αποκωδικοποιημένους χαρακτήρες.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |

### Τιμή επιστροφής

[Buffer](../../../system/buffer/) από αποκωδικοποιημένους χαρακτήρες.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |
| byte_count | int | Input buffer size. |
| chars | char_t * | [Buffer](../../../system/buffer/) για τοποθέτηση χαρακτήρων. |
| char_count | int | Output buffer size. |

### Τιμή επιστροφής

Αριθμός γραμμένων χαρακτήρων.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICUEncoding](../)
* Χώρος ονομάτων [System::Text](../../)
* Library [Aspose.Slides](../../../)