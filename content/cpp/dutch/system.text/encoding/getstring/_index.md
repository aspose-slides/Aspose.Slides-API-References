---
title: GetString()
second_title: Aspose.Slides for C++ API-referentie
description: Decodeert een buffer met bytes naar een string.
type: docs
weight: 313
url: /nl/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) methode

Decodeert een buffer met bytes naar een string.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) om bytes te lezen van. |
| byte_count | int | Grootte van de invoerbuffer. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) methode

Decodeert een buffer met bytes naar een string.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) om bytes te lezen van. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## Encoding::GetString(ArrayPtr\<uint8_t\>) methode

Decodeert een buffer met bytes naar een string.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen van. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) methode

Decodeert een buffer met bytes naar een string.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) om bytes te lezen van. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) methode

Decodeert een buffer met bytes naar een string.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) om bytes te lezen van. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) methode

Decodeert een buffer met bytes naar een string.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen van. |
| index | int | Offset van de invoerbuffer. |
| count | int | Grootte van de invoerbuffer. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) methode

Decodeert een buffer met bytes naar een string.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) om bytes te lezen van. |
| index | int | Offset van de invoerbuffer. |
| count | int | Grootte van de invoerbuffer. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) methode

Decodeert een buffer met bytes naar een string.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) om bytes te lezen van. |
| index | int | Offset van de invoerbuffer. |
| count | int | Grootte van de invoerbuffer. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [Encoding](../)
* Klasse [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)