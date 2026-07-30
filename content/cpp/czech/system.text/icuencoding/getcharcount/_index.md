---
title: GetCharCount()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá počet znaků potřebných k dekódování bytového bufferu.
type: docs
weight: 53
url: /cs/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) metoda


Získá počet znaků potřebných k dekódování bytového bufferu.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byty k dekódování. |
| count | int | Počet bytů. |

### Návratová hodnota

Počet znaků.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metoda


Získá počet znaků potřebných k dekódování bytového bufferu.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byty k dekódování. |
| index | int | Začátek řezu. |
| count | int | Velikost řezu. |

### Návratová hodnota

Počet znaků.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) metoda


Získá počet znaků potřebných k dekódování bytového bufferu.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byty k dekódování. |

### Návratová hodnota

Počet znaků.

## ICUEncoding::GetCharCount(const uint8_t *, int) metoda


Získá počet znaků potřebných k dekódování bytového bufferu.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byty k dekódování. |
| count | int | Počet bytů. |

### Návratová hodnota

Počet znaků.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICUEncoding](../)
* Jmenný prostor [System::Text](../../)
* Library [Aspose.Slides](../../../)