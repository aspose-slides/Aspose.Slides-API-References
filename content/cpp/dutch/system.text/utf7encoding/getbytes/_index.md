---
title: GetBytes()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.
type: docs
weight: 66
url: /nl/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekens om te coderen. |
| char_index | int | Begin van het tekenfragment. |
| char_count | int | Aantal tekens om te converteren. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| byte_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Tekens om te coderen. |
| char_count | int | Aantal tekens om te converteren. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| byte_count | int | Grootte van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) om te coderen. |
| char_index | int | Begin van het tekenfragment. |
| char_count | int | Aantal tekens om te converteren. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| byte_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekens om te coderen. |
| char_index | int | Begin van het tekenfragment. |
| char_count | int | Aantal tekens om te converteren. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| byte_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Tekens om te coderen. |
| char_index | int | Begin van het tekenfragment. |
| char_count | int | Aantal tekens om te converteren. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| byte_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Tekens om te coderen. |
| char_index | int | Begin van het tekenfragment. |
| char_count | int | Aantal tekens om te converteren. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| byte_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) om te coderen. |
| char_index | int | Begin van het tekenfragment. |
| char_count | int | Aantal tekens om te converteren. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| byte_index | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## UTF7Encoding::GetBytes(const String\&) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) om te coderen. |

### Retourwaarde

[Buffer](../../../system/buffer/) die een representatie bevat van de te coderen tekens.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekens om te coderen. |
| index | int | Begin van het tekenfragment. |
| count | int | Aantal tekens om te converteren. |

### Retourwaarde

[Buffer](../../../system/buffer/) die een representatie bevat van de te coderen tekens.

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Tekens om te coderen. |
| index | int | Begin van het tekenfragment. |
| count | int | Aantal tekens om te converteren. |

### Retourwaarde

[Buffer](../../../system/buffer/) die een representatie bevat van de te coderen tekens.

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Tekens om te coderen. |
| index | int | Begin van het tekenfragment. |
| count | int | Aantal tekens om te converteren. |

### Retourwaarde

[Buffer](../../../system/buffer/) die een representatie bevat van de te coderen tekens.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekens om te coderen. |

### Retourwaarde

[Buffer](../../../system/buffer/) die een representatie bevat van de te coderen tekens.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) method


Haalt de bytes op die voortkomen uit het coderen van een tekenbuffer.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Tekens om te coderen. |
| char_count | int | Aantal tekens om te converteren. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) om tekens te plaatsen. |
| byte_count | int | Grootte van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [UTF7Encoding](../)
* Klasse [String](../../../system/string/)
* Namespace [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)