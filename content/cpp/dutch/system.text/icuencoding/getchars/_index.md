---
title: GetChars()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal de tekens op die ontstaan bij het decoderen van een byte-buffer.
type: docs
weight: 66
url: /nl/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) methode

Haal de tekens op die ontstaan bij het decoderen van een byte-buffer.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) om bytes te lezen. |
| byte_count | int | Grootte van de invoerbuffer. |
| chars | char_t * | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| char_count | int | Grootte van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven tekens.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) methode

Haal de tekens op die ontstaan bij het decoderen van een byte-buffer.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |
| byte_index | int | Offset van de invoerbuffer. |
| byte_count | int | Grootte van de invoerbuffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| char_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven tekens.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) methode

Haal de tekens op die ontstaan bij het decoderen van een byte-buffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |
| index | int | Offset van de invoerbuffer. |
| count | int | Grootte van de invoerbuffer. |

### Retourwaarde

[Buffer](../../../system/buffer/) van gedecodeerde tekens.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) methode

Haal de tekens op die ontstaan bij het decoderen van een byte-buffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |

### Retourwaarde

[Buffer](../../../system/buffer/) van gedecodeerde tekens.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) methode

Haal de tekens op die ontstaan bij het decoderen van een byte-buffer.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) om bytes te lezen. |
| byte_count | int | Grootte van de invoerbuffer. |
| chars | char_t * | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| char_count | int | Grootte van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven tekens.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUEncoding](../)
* Namespace [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)