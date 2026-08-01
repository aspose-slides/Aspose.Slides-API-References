---
title: GetCharCount()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt het aantal tekens dat nodig is om een buffer te decoderen.
type: docs
weight: 40
url: /nl/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

Bepaalt het aantal tekens dat nodig is om een buffer te decoderen.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Aantal bytes om te decoderen. |

### Retourwaarde

Aantal tekens dat nodig is om de buffer te decoderen.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method

Bepaalt het aantal tekens dat nodig is om een buffer te decoderen.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Aantal bytes om te decoderen. |
| flush | **bool** | Als true, maakt de interne decoderstatus schoon na de berekening. |

### Retourwaarde

Aantal tekens dat nodig is om de buffer te decoderen.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) method

Bepaalt het aantal tekens dat nodig is om een buffer te decoderen.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes om te decoderen. |
| count | int | Aantal bytes om te decoderen. |
| flush | **bool** | Als true, maakt de interne decoderstatus schoon na de berekening. |

### Retourwaarde

Aantal tekens dat nodig is om de buffer te decoderen.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUDecoder](../)
* Namespace [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)