---
title: GetCharCount()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert het aantal tekens dat nodig is om een buffer te decoderen.
type: docs
weight: 40
url: /nl/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) methode


Retourneert het aantal tekens dat nodig is om een buffer te decoderen.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Aantal bytes om te decoderen. |

### Retourwaarde

Aantal tekens dat nodig is om de buffer te decoderen.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) methode


Retourneert het aantal tekens dat nodig is om een buffer te decoderen.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Aantal bytes om te decoderen. |
| flush | **bool** | Indien true, maakt de interne decoderstatus schoon na de berekening. |

### Retourwaarde

Aantal tekens dat nodig is om de buffer te decoderen.

## Decoder::GetCharCount(const uint8_t *, int, bool) methode


Retourneert het aantal tekens dat nodig is om een buffer te decoderen.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes om te decoderen. |
| count | int | Aantal bytes om te decoderen. |
| flush | **bool** | Indien true, maakt de interne decoderstatus schoon na de berekening. |

### Retourwaarde

Aantal tekens dat nodig is om de buffer te decoderen.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Decoder](../)
* Namespace [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)