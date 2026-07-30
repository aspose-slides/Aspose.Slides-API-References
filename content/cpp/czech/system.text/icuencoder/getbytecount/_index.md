---
title: GetByteCount()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací počet bajtů potřebných k zakódování bufferu.
type: docs
weight: 40
url: /cs/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metoda


Vrací počet bajtů potřebných k zakódování bufferu.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaky k zakódování. |
| index | int | [Buffer](../../../system/buffer/) posun. |
| count | int | Počet znaků k zakódování. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav enkodéru po výpočtu. |

### Návratová hodnota

Počet bajtů potřebných k zakódování bufferu.

## ICUEncoder::GetByteCount(const char_t *, int, bool) metoda


Vrací počet bajtů potřebných k zakódování bufferu.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Znaky k zakódování. |
| count | int | Počet znaků k zakódování. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav enkodéru po výpočtu. |

### Návratová hodnota

Počet bajtů potřebných k zakódování bufferu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICUEncoder](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)