---
title: GetCharCount()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt het aantal tekens op dat nodig is om een byte-buffer te decoderen.
type: docs
weight: 261
url: /nl/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

Haalt het aantal tekens op dat nodig is om een byte-buffer te decoderen.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| index | int | Begin van slice. |
| count | int | Grootte van slice. |

### Retourwaarde

Aantal tekens.

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) method

Haalt het aantal tekens op dat nodig is om een byte-buffer te decoderen.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |

### Retourwaarde

Aantal tekens.

## Encoding::GetCharCount(const uint8_t *, int) method

Haalt het aantal tekens op dat nodig is om een byte-buffer te decoderen.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes om te decoderen. |
| count | int | Aantal bytes. |

### Retourwaarde

Aantal tekens.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Encoding](../)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)