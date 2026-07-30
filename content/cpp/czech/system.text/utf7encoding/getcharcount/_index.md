---
title: GetCharCount()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá počet znaků potřebných k dekódování bufferu bajtů.
type: docs
weight: 79
url: /cs/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metoda

Získá počet znaků potřebných k dekódování bufferu bajtů.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty k dekódování. |
| index | int | Počátek výřezu. |
| count | int | Velikost výřezu. |

### Návratová hodnota

Počet znaků.

## UTF7Encoding::GetCharCount(const uint8_t *, int) metoda

Získá počet znaků potřebných k dekódování bufferu bajtů.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty k dekódování. |
| count | int | Počet bajtů. |

### Návratová hodnota

Počet znaků.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metoda

Získá počet znaků potřebných k dekódování bufferu bajtů.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty k dekódování. |
| index | int | Počátek výřezu. |
| count | int | Velikost výřezu. |

### Návratová hodnota

Počet znaků.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) metoda

Získá počet znaků potřebných k dekódování bufferu bajtů.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty k dekódování. |

### Návratová hodnota

Počet znaků.

## UTF7Encoding::GetCharCount(const uint8_t *, int) metoda

Získá počet znaků potřebných k dekódování bufferu bajtů.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty k dekódování. |
| count | int | Počet bajtů. |

### Návratová hodnota

Počet znaků.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [UTF7Encoding](../)
* Prostor názvů [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)