---
title: GetByteCount()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει τον αριθμό των χαρακτήρων που χρειάζονται για την κωδικοποίηση ενός buffer χαρακτήρων.
type: docs
weight: 27
url: /el/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) μέθοδος


Λαμβάνει τον αριθμό των χαρακτήρων που απαιτούνται για την κωδικοποίηση ενός πρόσθετου χαρακτήρων.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Πρόσθετο χαρακτήρων. |
| count | int | [Buffer](../../../system/buffer/) μέγεθος. |

### Τιμή επιστροφής

Απαιτούμενο μέγεθος του buffer.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) μέθοδος


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) μέθοδος


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) μέθοδος


RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) μέθοδος


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) μέθοδος


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) μέθοδος


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)