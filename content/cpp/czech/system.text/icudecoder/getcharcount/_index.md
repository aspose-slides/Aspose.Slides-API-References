---
title: GetCharCount()
second_title: Aspose.Slides pro C++ - referenční příručka
description: Získá počet znaků potřebných k dekódování bufferu.
type: docs
weight: 40
url: /cs/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metoda

Získá počet znaků potřebných k dekódování bufferu.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byty k dekódování. |
| index | int | [Buffer](../../../system/buffer/) posun. |
| count | int | Počet bytů k dekódování. |

### Návratová hodnota

Počet znaků potřebných k dekódování bufferu.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metoda


Získá počet znaků potřebných k dekódování bufferu.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byty k dekódování. |
| index | int | [Buffer](../../../system/buffer/) posun. |
| count | int | Počet bytů k dekódování. |
| flush | **bool** | Pokud je true, vyčistí interní stav dekodéru po výpočtu. |

### Návratová hodnota

Počet znaků potřebných k dekódování bufferu.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) metoda


Získá počet znaků potřebných k dekódování bufferu.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byty k dekódování. |
| count | int | Počet bytů k dekódování. |
| flush | **bool** | Pokud je true, vyčistí interní stav dekodéru po výpočtu. |

### Návratová hodnota

Počet znaků potřebných k dekódování bufferu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)