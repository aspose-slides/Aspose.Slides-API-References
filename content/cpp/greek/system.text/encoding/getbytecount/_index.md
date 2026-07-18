---
title: GetByteCount()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων.
type: docs
weight: 235
url: /el/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) μέθοδος

Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer χαρακτήρων. |
| index | int | Αρχή τμήματος. |
| count | int | Μέγεθος τμήματος. |

### Τιμή Επιστροφής

Απαιτούμενο μέγεθος buffer.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) μέθοδος

Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Buffer χαρακτήρων. |
| index | int | Αρχή τμήματος. |
| count | int | Μέγεθος τμήματος. |

### Τιμή Επιστροφής

Απαιτούμενο μέγεθος buffer.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) μέθοδος

Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Buffer χαρακτήρων. |
| index | int | Αρχή τμήματος. |
| count | int | Μέγεθος τμήματος. |

### Τιμή Επιστροφής

Απαιτούμενο μέγεθος buffer.

## Encoding::GetByteCount(const String\&) μέθοδος

Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση μιας συμβολοσειράς.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) για κωδικοποίηση. |

### Τιμή Επιστροφής

Απαιτούμενο μέγεθος buffer.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) μέθοδος

Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer χαρακτήρων. |

### Τιμή Επιστροφής

Απαιτούμενο μέγεθος buffer.

## Encoding::GetByteCount(const char_t *, int) μέθοδος

Επιστρέφει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός buffer χαρακτήρων.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chars | const char_t * | Buffer χαρακτήρων. |
| count | int | [Buffer](../../../system/buffer/) μέγεθος. |

### Τιμή Επιστροφής

Απαιτούμενο μέγεθος buffer.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Encoding](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)