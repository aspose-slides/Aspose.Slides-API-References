---
title: GetByteCount()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá počet znaků potřebných pro zakódování bufferu znaků.
type: docs
weight: 157
url: /cs/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) method

Získá počet znaků potřebných pro zakódování bufferu znaků.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Buffer znaků. |
| count | int | [Buffer](../../../system/buffer/) velikost. |

### Návratová hodnota

Požadovaná velikost bufferu.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) method

Získá počet znaků potřebných pro zakódování bufferu znaků.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer znaků. |
| index | int | Začátek řezu. |
| count | int | Velikost řezu. |

### Návratová hodnota

Požadovaná velikost bufferu.

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) method

Získá počet znaků potřebných pro zakódování bufferu znaků.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Buffer znaků. |
| index | int | Začátek řezu. |
| count | int | Velikost řezu. |

### Návratová hodnota

Požadovaná velikost bufferu.

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) method

Získá počet znaků potřebných pro zakódování bufferu znaků.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Buffer znaků. |
| index | int | Začátek řezu. |
| count | int | Velikost řezu. |

### Návratová hodnota

Požadovaná velikost bufferu.

## UTF7Encoding::GetByteCount(const String\&) method

Získá počet znaků potřebných pro zakódování řetězce.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) k zakódování. |

### Návratová hodnota

Požadovaná velikost bufferu.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) method

Získá počet znaků potřebných pro zakódování bufferu znaků.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer znaků. |

### Návratová hodnota

Požadovaná velikost bufferu.

## UTF7Encoding::GetByteCount(const char_t *, int) method

Získá počet znaků potřebných pro zakódování bufferu znaků.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Buffer znaků. |
| count | int | [Buffer](../../../system/buffer/) velikost. |

### Návratová hodnota

Požadovaná velikost bufferu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)