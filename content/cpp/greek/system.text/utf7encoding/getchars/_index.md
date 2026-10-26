---
title: GetChars()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.
type: docs
weight: 92
url: /el/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση bytes από. |
| byte_index | int | Μετατόπιση buffer εισόδου. |
| byte_count | int | Μέγεθος buffer εισόδου. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) για τοποθέτηση χαρακτήρων. |
| char_index | int | Μετατόπιση buffer εξόδου. |

### Τιμή Επιστροφής

Αριθμός γραμμένων χαρακτήρων.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) για ανάγνωση bytes από. |
| byte_count | int | Μέγεθος buffer εισόδου. |
| chars | char_t * | [Buffer](../../../system/buffer/) για τοποθέτηση χαρακτήρων. |
| char_count | int | Μέγεθος buffer εξόδου. |

### Τιμή Επιστροφής

Αριθμός γραμμένων χαρακτήρων.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση bytes από. |
| byte_index | int | Μετατόπιση buffer εισόδου. |
| byte_count | int | Μέγεθος buffer εισόδου. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) για τοποθέτηση χαρακτήρων. |
| char_index | int | Μετατόπιση buffer εξόδου. |

### Τιμή Επιστροφής

Αριθμός γραμμένων χαρακτήρων.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση bytes από. |
| index | int | Μετατόπιση buffer εισόδου. |
| count | int | Μέγεθος buffer εισόδου. |

### Τιμή Επιστροφής

[Buffer](../../../system/buffer/) των αποκωδικοποιημένων χαρακτήρων.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση bytes από. |

### Τιμή Επιστροφής

[Buffer](../../../system/buffer/) των αποκωδικοποιημένων χαρακτήρων.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) μέθοδος

Λαμβάνει τους χαρακτήρες που προκύπτουν από την αποκωδικοποίηση ενός byte buffer.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) για ανάγνωση bytes από. |
| byte_count | int | Μέγεθος buffer εισόδου. |
| chars | char_t * | [Buffer](../../../system/buffer/) για τοποθέτηση χαρακτήρων. |
| char_count | int | Μέγεθος buffer εξόδου. |

### Τιμή Επιστροφής

Αριθμός γραμμένων χαρακτήρων.

## Δείτε επίσης

* Ορισμός τύπου [ArrayPtr](../../../system/arrayptr/)
* Κλάση [UTF7Encoding](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)