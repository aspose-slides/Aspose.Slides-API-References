---
title: GetByteCount()
second_title: Referenční příručka API pro Aspose.Slides pro C++
description: Získá počet bytů potřebných pro zakódování bufferu.
type: docs
weight: 40
url: /cs/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metoda


Gets the number of bytes needed to encode a buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaky k zakódování. |
| index | int | [Buffer](../../../system/buffer/) posun. |
| count | int | Počet znaků k zakódování. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav enkodéru po výpočtu. |

### Návratová hodnota

Number of bytes required to encode the buffer.

## Encoder::GetByteCount(const char_t *, int, bool) metoda


Gets the number of bytes needed to encode a buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Znaky k zakódování. |
| count | int | Počet znaků k zakódování. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav enkodéru po výpočtu. |

### Návratová hodnota

Number of bytes required to encode the buffer.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Encoder](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)