---
title: GetBytes()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.
type: docs
weight: 40
url: /el/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const char_t * | Χαρακτήρες προς κωδικοποίηση. |
| char_count | int | Αριθμός χαρακτήρων προς μετατροπή. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) για αποθήκευση χαρακτήρων. |
| byte_count | int | Μέγεθος εξαγόμενου buffer. |

### Τιμή Επιστροφής

Αριθμός των γραμμένων byte.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Παράμεtroι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Χαρακτήρες προς κωδικοποίηση. |
| char_index | int | Αρχή τμήματος χαρακτήρων. |
| char_count | int | Αριθμός χαρακτήρων προς μετατροπή. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για αποθήκευση χαρακτήρων. |
| byte_index | int | Μετατόπιση εξαγόμενου buffer. |

### Τιμή Επιστροφής

Αριθμός των γραμμένων byte.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Χαρακτήρες προς κωδικοποίηση. |
| char_index | int | Αρχή τμήματος χαρακτήρων. |
| char_count | int | Αριθμός χαρακτήρων προς μετατροπή. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) για αποθήκευση χαρακτήρων. |
| byte_index | int | Μετατόπιση εξαγόμενου buffer. |

### Τιμή Επιστροφής

Αριθμός των γραμμένων byte.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Χαρακτήρες προς κωδικοποίηση. |
| char_index | int | Αρχή τμήματος χαρακτήρων. |
| char_count | int | Αριθμός χαρακτήρων προς μετατροπή. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) για αποθήκευση χαρακτήρων. |
| byte_index | int | Μετατόπιση εξαγόμενου buffer. |

### Τιμή Επιστροφής

Αριθμός των γραμμένων byte.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) για κωδικοποίηση. |
| char_index | int | Αρχή τμήματος χαρακτήρων. |
| char_count | int | Αριθμός χαρακτήρων προς μετατροπή. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για αποθήκευση χαρακτήρων. |
| byte_index | int | Μετατόπιση εξαγόμενου buffer. |

### Τιμή Επιστροφής

Αριθμός των γραμμένων byte.

## ICUEncoding::GetBytes(const String\&) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) για κωδικοποίηση. |

### Τιμή Επιστροφής

[Buffer](../../../system/buffer/) που περιέχει την αναπαράσταση των χαρακτήρων που κωδικοποιούνται.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Χαρακτήρες προς κωδικοποίηση. |
| index | int | Αρχή τμήματος χαρακτήρων. |
| count | int | Αριθμός χαρακτήρων προς μετατροπή. |

### Τιμή Επιστροφής

[Buffer](../../../system/buffer/) που περιέχει την αναπαράσταση των χαρακτήρων που κωδικοποιούνται.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Χαρακτήρες προς κωδικοποίηση. |
| index | int | Αρχή τμήματος χαρακτήρων. |
| count | int | Αριθμός χαρακτήρων προς μετατροπή. |

### Τιμή Επιστροφής

[Buffer](../../../system/buffer/) που περιέχει την αναπαράσταση των χαρακτήρων που κωδικοποιούνται.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Παράμεtroι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Χαρακτήρες προς κωδικοποίηση. |
| index | int | Αρχή τμήματος χαρακτήρων. |
| count | int | Αριθμός χαρακτήρων προς μετατροπή. |

### Τιμή Επιστροφής

[Buffer](../../../system/buffer/) που περιέχει την αναπαράσταση των χαρακτήρων που κωδικοποιούνται.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Χαρακτήρες προς κωδικοποίηση. |

### Τιμή Επιστροφής

[Buffer](../../../system/buffer/) που περιέχει την αναπαράσταση των χαρακτήρων που κωδικοποιούνται.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) μέθοδος

Λαμβάνει τα byte που προκύπτουν από την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Παράμεtroι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const char_t * | Χαρακτήρες προς κωδικοποίηση. |
| char_count | int | Αριθμός χαρακτήρων προς μετατροπή. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) για αποθήκευση χαρακτήρων. |
| byte_count | int | Μέγεθος εξαγόμενου buffer. |

### Τιμή Επιστροφής

Αριθμός των γραμμένων byte.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICUEncoding](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)