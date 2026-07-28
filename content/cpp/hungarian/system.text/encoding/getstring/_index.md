---
title: GetString()
second_title: Aspose.Slides C++ API-referencia
description: Dekódolja a bájtok pufferét egy karakterláncba.
type: docs
weight: 313
url: /hu/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) metódus


Dekódolja a bájtok pufferét egy karakterláncba.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) a bájtok olvasásához. |
| byte_count | int | Bemeneti puffer mérete. |

### Visszatérési érték

[String](../../../system/string/) a dekódolt karakterek.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) metódus


Dekódolja a bájtok pufferét egy karakterláncba.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) a bájtok olvasásához. |

### Visszatérési érték

[String](../../../system/string/) a dekódolt karakterek.

## Encoding::GetString(ArrayPtr\<uint8_t\>) metódus


Dekódolja a bájtok pufferét egy karakterláncba.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a bájtok olvasásához. |

### Visszatérési érték

[String](../../../system/string/) a dekódolt karakterek.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) metódus


Dekódolja a bájtok pufferét egy karakterláncba.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) a bájtok olvasásához. |

### Visszatérési érték

[String](../../../system/string/) a dekódolt karakterek.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) metódus


Dekódolja a bájtok pufferét egy karakterláncba.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) a bájtok olvasásához. |

### Visszatérési érték

[String](../../../system/string/) a dekódolt karakterek.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) metódus


Dekódolja a bájtok pufferét egy karakterláncba.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a bájtok olvasásához. |
| index | int | Bemeneti puffer eltolása. |
| count | int | Bemeneti puffer mérete. |

### Visszatérési érték

[String](../../../system/string/) a dekódolt karakterek.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) metódus


Dekódolja a bájtok pufferét egy karakterláncba.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) a bájtok olvasásához. |
| index | int | Bemeneti puffer eltolása. |
| count | int | Bemeneti puffer mérete. |

### Visszatérési érték

[String](../../../system/string/) a dekódolt karakterek.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) metódus


Dekódolja a bájtok pufferét egy karakterláncba.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) a bájtok olvasásához. |
| index | int | Bemeneti puffer eltolása. |
| count | int | Bemeneti puffer mérete. |

### Visszatérési érték

[String](../../../system/string/) a dekódolt karakterek.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* osztály [String](../../../system/string/)
* osztály [Encoding](../)
* osztály [ReadOnlySpan](../../../system/readonlyspan/)
* névtér [System::Text](../../)
* Library [Aspose.Slides](../../../)