---
title: GetString()
second_title: Aspose.Slides voor C++ API-referentie
description: Decodeert een buffer met bytes naar een string.
type: docs
weight: 170
url: /nl/system.text/utf7encoding/getstring/
---
## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) methode

Decodeert een buffer met bytes naar een string.

```cpp
String System::Text::UTF7Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## UTF7Encoding::GetString(uint8_t *, int) methode

Decodeert een buffer met bytes naar een string.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) om bytes te lezen. |
| byte_count | int | Input buffer size. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## UTF7Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) methode

Decodeert een buffer met bytes naar een string.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) om bytes te lezen. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>) methode

Decodeert een buffer met bytes naar een string.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) methode

Decodeert een buffer met bytes naar een string.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) om bytes te lezen. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) methode

Decodeert een buffer met bytes naar een string.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) om bytes te lezen. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) methode

Decodeert een buffer met bytes naar een string.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om bytes te lezen. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) methode

Decodeert een buffer met bytes naar een string.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) om bytes te lezen. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) methode

Decodeert een buffer met bytes naar een string.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) om bytes te lezen. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Retourwaarde

[String](../../../system/string/) van gedecodeerde tekens.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [UTF7Encoding](../)
* Klasse [ReadOnlySpan](../../../system/readonlyspan/)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)