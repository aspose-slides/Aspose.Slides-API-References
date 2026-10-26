---
title: GetBytes()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal de bytes op die voortkomen uit het coderen van een tekenbuffer.
type: docs
weight: 248
url: /nl/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) methode

Ontvang de bytes die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekens om te coderen. |
| char_index | int | Begin van het tekenfragment. |
| char_count | int | Aantal te converteren tekens. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om tekens in te plaatsen. |
| byte_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) methode

Ontvang de bytes die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Tekens om te coderen. |
| char_index | int | Begin van het tekenfragment. |
| char_count | int | Aantal te converteren tekens. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) om tekens in te plaatsen. |
| byte_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) methode

Ontvang de bytes die voortkomen uit het coderen van een tekenbuffer.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Tekens om te coderen. |
| char_index | int | Begin van het tekenfragment. |
| char_count | int | Aantal te converteren tekens. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) om tekens in te plaatsen. |
| byte_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) methode

Ontvang de bytes die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) om te coderen. |
| char_index | int | Begin van het tekenfragment. |
| char_count | int | Aantal te converteren tekens. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om tekens in te plaatsen. |
| byte_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## Encoding::GetBytes(const String\&) methode

Ontvang de bytes die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) om te coderen. |

### Retourwaarde

[Buffer](../../../system/buffer/) die de representatie van de te coderen tekens bevat.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) methode

Ontvang de bytes die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekens om te coderen. |
| index | int | Begin van het tekenfragment. |
| count | int | Aantal te converteren tekens. |

### Retourwaarde

[Buffer](../../../system/buffer/) die de representatie van de te coderen tekens bevat.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) methode

Ontvang de bytes die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Tekens om te coderen. |
| index | int | Begin van het tekenfragment. |
| count | int | Aantal te converteren tekens. |

### Retourwaarde

[Buffer](../../../system/buffer/) die de representatie van de te coderen tekens bevat.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) methode

Ontvang de bytes die voortkomen uit het coderen van een tekenbuffer.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Tekens om te coderen. |
| index | int | Begin van het tekenfragment. |
| count | int | Aantal te converteren tekens. |

### Retourwaarde

[Buffer](../../../system/buffer/) die de representatie van de te coderen tekens bevat.

## Encoding::GetBytes(ArrayPtr\<char_t\>) methode

Ontvang de bytes die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekens om te coderen. |

### Retourwaarde

[Buffer](../../../system/buffer/) die de representatie van de te coderen tekens bevat.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) methode

Ontvang de bytes die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | const char_t * | Tekens om te coderen. |
| char_count | int | Aantal te converteren tekens. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) om tekens in te plaatsen. |
| byte_count | int | Grootte van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)