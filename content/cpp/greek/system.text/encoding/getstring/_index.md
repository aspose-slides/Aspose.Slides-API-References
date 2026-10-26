---
title: GetString()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά.
type: docs
weight: 313
url: /el/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) μέθοδος

Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |
| byte_count | int | Μέγεθος buffer εισόδου. |

### Τιμή Επιστροφής

[String](../../../system/string/) των αποκωδικοποιημένων χαρακτήρων.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) μέθοδος

Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |

### Τιμή Επιστροφής

[String](../../../system/string/) των αποκωδικοποιημένων χαρακτήρων.

## Encoding::GetString(ArrayPtr\<uint8_t\>) μέθοδος

Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |

### Τιμή Επιστροφής

[String](../../../system/string/) των αποκωδικοποιημένων χαρακτήρων.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) μέθοδος

Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |

### Τιμή Επιστροφής

[String](../../../system/string/) των αποκωδικοποιημένων χαρακτήρων.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) μέθοδος

Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |

### Τιμή Επιστροφής

[String](../../../system/string/) των αποκωδικοποιημένων χαρακτήρων.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) μέθοδος

Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |
| index | int | Μετατόπιση buffer εισόδου. |
| count | int | Μέγεθος buffer εισόδου. |

### Τιμή Επιστροφής

[String](../../../system/string/) των αποκωδικοποιημένων χαρακτήρων.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) μέθοδος

Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |
| index | int | Μετατόπιση buffer εισόδου. |
| count | int | Μέγεθος buffer εισόδου. |

### Τιμή Επιστροφής

[String](../../../system/string/) των αποκωδικοποιημένων χαρακτήρων.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) μέθοδος

Αποκωδικοποιεί ένα buffer byte σε μια συμβολοσειρά.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) για ανάγνωση bytes. |
| index | int | Μετατόπιση buffer εισόδου. |
| count | int | Μέγεθος buffer εισόδου. |

### Τιμή Επιστροφής

[String](../../../system/string/) των αποκωδικοποιημένων χαρακτήρων.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Encoding](../)
* Κλάση [ReadOnlySpan](../../../system/readonlyspan/)
* Χώρος ονομάτων [System::Text](../../)
* Library [Aspose.Slides](../../../)