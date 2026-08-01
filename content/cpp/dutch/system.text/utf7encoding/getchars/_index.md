---
title: GetChars()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal de tekens op die het resultaat zijn van het decoderen van een bytebuffer.
type: docs
weight: 92
url: /nl/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) methode

Haal de tekens op die het resultaat zijn van het decoderen van een bytebuffer.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |
| byte_index | int | Offset van invoerbuffer. |
| byte_count | int | Grootte van invoerbuffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| char_index | int | Offset van uitvoerbuffer. |

### Retourwaarde

Aantal geschreven tekens.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) methode

Haal de tekens op die het resultaat zijn van het decoderen van een bytebuffer.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) om bytes te lezen. |
| byte_count | int | Grootte van invoerbuffer. |
| chars | char_t * | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| char_count | int | Grootte van uitvoerbuffer. |

### Retourwaarde

Aantal geschreven tekens.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) methode

Haal de tekens op die het resultaat zijn van het decoderen van een bytebuffer.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |
| byte_index | int | Offset van invoerbuffer. |
| byte_count | int | Grootte van invoerbuffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| char_index | int | Offset van uitvoerbuffer. |

### Retourwaarde

Aantal geschreven tekens.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) methode

Haal de tekens op die het resultaat zijn van het decoderen van een bytebuffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |
| index | int | Offset van invoerbuffer. |
| count | int | Grootte van invoerbuffer. |

### Retourwaarde

[Buffer](../../../system/buffer/) van gedecodeerde tekens.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) methode

Haal de tekens op die het resultaat zijn van het decoderen van een bytebuffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |

### Retourwaarde

[Buffer](../../../system/buffer/) van gedecodeerde tekens.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) methode

Haal de tekens op die het resultaat zijn van het decoderen van een bytebuffer.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) om bytes te lezen. |
| byte_count | int | Grootte van invoerbuffer. |
| chars | char_t * | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| char_count | int | Grootte van uitvoerbuffer. |

### Retourwaarde

Aantal geschreven tekens.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)