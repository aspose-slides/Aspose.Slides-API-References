---
title: GetByteCount()
second_title: Aspose.Slides для C++ API справочник
description: Получает количество символов, необходимых для кодирования буфера символов.
type: docs
weight: 27
url: /ru/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) метод

Получает количество символов, необходимых для кодирования буфера символов.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const char_t * | Буфер символов. |
| count | int | размер [Buffer](../../../system/buffer/). |

### Возвращаемое значение

Требуемый размер буфера.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) метод

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) метод

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) метод

RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) метод

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) метод

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) метод

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## Смотрите также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICUEncoding](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)