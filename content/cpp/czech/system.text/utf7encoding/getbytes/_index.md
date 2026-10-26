---
title: GetBytes()
second_title: Aspose.Slides pro C++ - reference API
description: Získá bajty, které vzniknou kódováním znakové paměti.
type: docs
weight: 66
url: /cs/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaků k zakódování. |
| char_index | int | Počátek výřezu znaků. |
| char_count | int | Počet znaků k převedení. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) k vložení znaků. |
| byte_index | int | Posun výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Znaků k zakódování. |
| char_count | int | Počet znaků k převedení. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) k vložení znaků. |
| byte_count | int | Velikost výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) k zakódování. |
| char_index | int | Počátek výřezu znaků. |
| char_count | int | Počet znaků k převedení. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) k vložení znaků. |
| byte_index | int | Posun výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaků k zakódování. |
| char_index | int | Počátek výřezu znaků. |
| char_count | int | Počet znaků k převedení. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) k vložení znaků. |
| byte_index | int | Posun výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Znaků k zakódování. |
| char_index | int | Počátek výřezu znaků. |
| char_count | int | Počet znaků k převedení. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) k vložení znaků. |
| byte_index | int | Posun výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Znaků k zakódování. |
| char_index | int | Počátek výřezu znaků. |
| char_count | int | Počet znaků k převedení. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) k vložení znaků. |
| byte_index | int | Posun výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) k zakódování. |
| char_index | int | Počátek výřezu znaků. |
| char_count | int | Počet znaků k převedení. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) k vložení znaků. |
| byte_index | int | Posun výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## UTF7Encoding::GetBytes(const String\&) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) k zakódování. |

### Návratová hodnota

[Buffer](../../../system/buffer/) který obsahuje reprezentaci kódovaných znaků.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaků k zakódování. |
| index | int | Počátek výřezu znaků. |
| count | int | Počet znaků k převedení. |

### Návratová hodnota

[Buffer](../../../system/buffer/) který obsahuje reprezentaci kódovaných znaků.

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Znaků k zakódování. |
| index | int | Počátek výřezu znaků. |
| count | int | Počet znaků k převedení. |

### Návratová hodnota

[Buffer](../../../system/buffer/) který obsahuje reprezentaci kódovaných znaků.

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Znaků k zakódování. |
| index | int | Počátek výřezu znaků. |
| count | int | Počet znaků k převedení. |

### Návratová hodnota

[Buffer](../../../system/buffer/) který obsahuje reprezentaci kódovaných znaků.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaků k zakódování. |

### Návratová hodnota

[Buffer](../../../system/buffer/) který obsahuje reprezentaci kódovaných znaků.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) method

Získá bajty, které vzniknou kódováním znakové paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Znaků k zakódování. |
| char_count | int | Počet znaků k převedení. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) k vložení znaků. |
| byte_count | int | Velikost výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)