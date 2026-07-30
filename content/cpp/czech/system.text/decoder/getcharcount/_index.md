---
title: GetCharCount()
second_title: Aspose.Slides pro C++ – reference API
description: Získá počet znaků potřebných k dekódování bufferu.
type: docs
weight: 40
url: /cs/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metoda

Získá počet znaků potřebných k dekódování bufferu.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty k dekódování. |
| index | int | [Buffer](../../../system/buffer/) posun. |
| count | int | Počet bajtů k dekódování. |

### Návratová hodnota

Počet znaků potřebných pro dekódování bufferu.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metoda

Získá počet znaků potřebných k dekódování bufferu.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty k dekódování. |
| index | int | [Buffer](../../../system/buffer/) posun. |
| count | int | Počet bajtů k dekódování. |
| flush | **bool** | Pokud je true, vyčistí interní stav dekodéru po výpočtu. |

### Návratová hodnota

Počet znaků potřebných pro dekódování bufferu.

## Decoder::GetCharCount(const uint8_t *, int, bool) metoda

Získá počet znaků potřebných k dekódování bufferu.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty k dekódování. |
| count | int | Počet bajtů k dekódování. |
| flush | **bool** | Pokud je true, vyčistí interní stav dekodéru po výpočtu. |

### Návratová hodnota

Počet znaků potřebných pro dekódování bufferu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)