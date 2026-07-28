---
title: GetBytes()
second_title: Aspose.Slides for C++ API-referencia
description: A karakterpuffer kódolásából származó bájtokat adja vissza.
type: docs
weight: 66
url: /hu/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kódolandó karakterek. |
| char_index | int | Karakterdarab kezdete. |
| char_count | int | Átalakítandó karakterek száma. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a karakterek elhelyezésére. |
| byte_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | Kódolandó karakterek. |
| char_count | int | Átalakítandó karakterek száma. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) a karakterek elhelyezésére. |
| byte_count | int | Kimeneti puffer mérete. |

### Visszatérési érték

Az írt bájtok száma.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) a kódoláshoz. |
| char_index | int | Karakterdarab kezdete. |
| char_count | int | Átalakítandó karakterek száma. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a karakterek elhelyezésére. |
| byte_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kódolandó karakterek. |
| char_index | int | Karakterdarab kezdete. |
| char_count | int | Átalakítandó karakterek száma. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a karakterek elhelyezésére. |
| byte_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Kódolandó karakterek. |
| char_index | int | Karakterdarab kezdete. |
| char_count | int | Átalakítandó karakterek száma. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) a karakterek elhelyezésére. |
| byte_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Kódolandó karakterek. |
| char_index | int | Karakterdarab kezdete. |
| char_count | int | Átalakítandó karakterek száma. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) a karakterek elhelyezésére. |
| byte_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) a kódoláshoz. |
| char_index | int | Karakterdarab kezdete. |
| char_count | int | Átalakítandó karakterek száma. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a karakterek elhelyezésére. |
| byte_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## UTF7Encoding::GetBytes(const String\&) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) a kódoláshoz. |

### Visszatérési érték

[Buffer](../../../system/buffer/) amely a kódolt karakterek ábrázolását tartalmazza.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kódolandó karakterek. |
| index | int | Karakterdarab kezdete. |
| count | int | Átalakítandó karakterek száma. |

### Visszatérési érték

[Buffer](../../../system/buffer/) amely a kódolt karakterek ábrázolását tartalmazza.

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Kódolandó karakterek. |
| index | int | Karakterdarab kezdete. |
| count | int | Átalakítandó karakterek száma. |

### Visszatérési érték

[Buffer](../../../system/buffer/) amely a kódolt karakterek ábrázolását tartalmazza.

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Kódolandó karakterek. |
| index | int | Karakterdarab kezdete. |
| count | int | Átalakítandó karakterek száma. |

### Visszatérési érték

[Buffer](../../../system/buffer/) amely a kódolt karakterek ábrázolását tartalmazza.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kódolandó karakterek. |

### Visszatérési érték

[Buffer](../../../system/buffer/) amely a kódolt karakterek ábrázolását tartalmazza.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) metódus


A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | Kódolandó karakterek. |
| char_count | int | Átalakítandó karakterek száma. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) a karakterek elhelyezésére. |
| byte_count | int | Kimeneti puffer mérete. |

### Visszatérési érték

Az írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)