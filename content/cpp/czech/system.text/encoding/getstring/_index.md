---
title: GetString()
second_title: Aspose.Slides pro C++ API Reference
description: Dekóduje buffer bajtů do řetězce.
type: docs
weight: 313
url: /cs/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) metoda


Dekóduje buffer bajtů do řetězce.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) k načtení bajtů z. |
| byte_count | int | Velikost vstupního bufferu. |

### Návratová hodnota

[String](../../../system/string/) dekódovaných znaků.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) metoda


Dekóduje buffer bajtů do řetězce.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) k načtení bajtů z. |

### Návratová hodnota

[String](../../../system/string/) dekódovaných znaků.

## Encoding::GetString(ArrayPtr\<uint8_t\>) metoda


Dekóduje buffer bajtů do řetězce.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) k načtení bajtů z. |

### Návratová hodnota

[String](../../../system/string/) dekódovaných znaků.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) metoda


Dekóduje buffer bajtů do řetězce.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) k načtení bajtů z. |

### Návratová hodnota

[String](../../../system/string/) dekódovaných znaků.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) metoda


Dekóduje buffer bajtů do řetězce.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) k načtení bajtů z. |

### Návratová hodnota

[String](../../../system/string/) dekódovaných znaků.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) metoda


Dekóduje buffer bajtů do řetězce.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) k načtení bajtů z. |
| index | int | Posun vstupního bufferu. |
| count | int | Velikost vstupního bufferu. |

### Návratová hodnota

[String](../../../system/string/) dekódovaných znaků.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) metoda


Dekóduje buffer bajtů do řetězce.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) k načtení bajtů z. |
| index | int | Posun vstupního bufferu. |
| count | int | Velikost vstupního bufferu. |

### Návratová hodnota

[String](../../../system/string/) dekódovaných znaků.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) metoda


Dekóduje buffer bajtů do řetězce.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) k načtení bajtů z. |
| index | int | Posun vstupního bufferu. |
| count | int | Velikost vstupního bufferu. |

### Návratová hodnota

[String](../../../system/string/) dekódovaných znaků.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [Encoding](../)
* Třída [ReadOnlySpan](../../../system/readonlyspan/)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)