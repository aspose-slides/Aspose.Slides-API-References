---
title: GetByteCount()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Získá počet znaků potřebných k zakódování bufferu znaků.
type: docs
weight: 235
url: /cs/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metoda


Získá počet znaků potřebných k zakódování bufferu znaků.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer znaků. |
| index | int | Začátek výřezu. |
| count | int | Velikost výřezu. |

### Návratová hodnota

Požadovaná velikost bufferu.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metoda


Získá počet znaků potřebných k zakódování bufferu znaků.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Buffer znaků. |
| index | int | Začátek výřezu. |
| count | int | Velikost výřezu. |

### Návratová hodnota

Požadovaná velikost bufferu.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metoda


Získá počet znaků potřebných k zakódování bufferu znaků.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Buffer znaků. |
| index | int | Začátek výřezu. |
| count | int | Velikost výřezu. |

### Návratová hodnota

Požadovaná velikost bufferu.

## Encoding::GetByteCount(const String\&) metoda


Získá počet znaků potřebných k zakódování řetězce.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) k zakódování. |

### Návratová hodnota

Požadovaná velikost bufferu.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) metoda


Získá počet znaků potřebných k zakódování bufferu znaků.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer znaků. |

### Návratová hodnota

Požadovaná velikost bufferu.

## Encoding::GetByteCount(const char_t *, int) metoda


Získá počet znaků potřebných k zakódování bufferu znaků.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Buffer znaků. |
| count | int | Velikost [Buffer](../../../system/buffer/). |

### Návratová hodnota

Požadovaná velikost bufferu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Encoding](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)