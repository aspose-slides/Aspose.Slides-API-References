---
title: GetByteCount()
second_title: Справочник API Aspose.Slides для C++
description: Получает количество символов, необходимых для кодирования буфера символов.
type: docs
weight: 235
url: /ru/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) метод

Возвращает количество символов, необходимых для кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Буфер символов. |
| index | int | Начало среза. |
| count | int | Размер среза. |

### Возвращаемое значение

Требуемый размер буфера.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) метод

Возвращает количество символов, необходимых для кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Буфер символов. |
| index | int | Начало среза. |
| count | int | Размер среза. |

### Возвращаемое значение

Требуемый размер буфера.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) метод

Возвращает количество символов, необходимых для кодирования буфера символов.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Буфер символов. |
| index | int | Начало среза. |
| count | int | Размер среза. |

### Возвращаемое значение

Требуемый размер буфера.

## Encoding::GetByteCount(const String\&) метод

Возвращает количество символов, необходимых для кодирования строки.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) для кодирования. |

### Возвращаемое значение

Требуемый размер буфера.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) метод

Возвращает количество символов, необходимых для кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Буфер символов. |

### Возвращаемое значение

Требуемый размер буфера.

## Encoding::GetByteCount(const char_t *, int) метод

Возвращает количество символов, необходимых для кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const char_t * | Буфер символов. |
| count | int | [Buffer](../../../system/buffer/) размер. |

### Возвращаемое значение

Требуемый размер буфера.

## Смотрите также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [Encoding](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)