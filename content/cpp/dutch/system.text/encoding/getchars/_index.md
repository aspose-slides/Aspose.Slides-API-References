---
title: GetChars()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal de tekens op die voortkomen uit het decoderen van een bytebuffer.
type: docs
weight: 274
url: /nl/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) methode


Haal de tekens op die voortkomen uit het decoderen van een bytebuffer.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |
| byte_index | int | Inputbuffer-offset. |
| byte_count | int | Inputbuffer-grootte. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| char_index | int | Outputbuffer-offset. |

### Retourwaarde

Aantal geschreven tekens.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) methode


Haal de tekens op die voortkomen uit het decoderen van een bytebuffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |
| index | int | Inputbuffer-offset. |
| count | int | Inputbuffer-grootte. |

### Retourwaarde

[Buffer](../../../system/buffer/) van gedecodeerde tekens.

## Encoding::GetChars(ArrayPtr\<uint8_t\>) methode


Haal de tekens op die voortkomen uit het decoderen van een bytebuffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |

### Retourwaarde

[Buffer](../../../system/buffer/) van gedecodeerde tekens.

## Encoding::GetChars(const uint8_t *, int, char_t *, int) methode


Haal de tekens op die voortkomen uit het decoderen van een bytebuffer.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) om bytes te lezen. |
| byte_count | int | Inputbuffer-grootte. |
| chars | char_t * | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| char_count | int | Outputbuffer-grootte. |

### Retourwaarde

Aantal geschreven tekens.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Encoding](../)
* Namespace [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)