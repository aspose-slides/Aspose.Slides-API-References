---
title: GetBytes()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a karakterpuffer kódolásából származó bájtokat.
type: docs
weight: 248
url: /hu/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kódolandó karakterek. |
| char_index | int | Karakter szelet kezdete. |
| char_count | int | Átkonvertálandó karakterek száma. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| byte_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method

A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Kódolandó karakterek. |
| char_index | int | Karakter szelet kezdete. |
| char_count | int | Átkonvertálandó karakterek száma. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| byte_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method

A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Kódolandó karakterek. |
| char_index | int | Karakter szelet kezdete. |
| char_count | int | Átkonvertálandó karakterek száma. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| byte_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method

A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) a kódoláshoz. |
| char_index | int | Karakter szelet kezdete. |
| char_count | int | Átkonvertálandó karakterek száma. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| byte_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## Encoding::GetBytes(const String\&) method

A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) a kódoláshoz. |

### Visszatérési érték

[Buffer](../../../system/buffer/) amely a kódolt karakterek ábrázolását tartalmazza.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) method

A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kódolandó karakterek. |
| index | int | Karakter szelet kezdete. |
| count | int | Átkonvertálandó karakterek száma. |

### Visszatérési érték

[Buffer](../../../system/buffer/) amely a kódolt karakterek ábrázolását tartalmazza.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method

A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Kódolandó karakterek. |
| index | int | Karakter szelet kezdete. |
| count | int | Átkonvertálandó karakterek száma. |

### Visszatérési érték

[Buffer](../../../system/buffer/) amely a kódolt karakterek ábrázolását tartalmazza.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method

A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Kódolandó karakterek. |
| index | int | Karakter szelet kezdete. |
| count | int | Átkonvertálandó karakterek száma. |

### Visszatérési érték

[Buffer](../../../system/buffer/) amely a kódolt karakterek ábrázolását tartalmazza.

## Encoding::GetBytes(ArrayPtr\<char_t\>) method

A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kódolandó karakterek. |

### Visszatérési érték

[Buffer](../../../system/buffer/) amely a kódolt karakterek ábrázolását tartalmazza.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) method

A karakterpuffer kódolásából származó bájtokat adja vissza.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Kódolandó karakterek. |
| char_count | int | Átkonvertálandó karakterek száma. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| byte_count | int | Kimeneti puffer mérete. |

### Visszatérési érték

Az írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Encoding](../)
* Osztály [String](../../../system/string/)
* Névtere [System::Text](../../)
* Library [Aspose.Slides](../../../)