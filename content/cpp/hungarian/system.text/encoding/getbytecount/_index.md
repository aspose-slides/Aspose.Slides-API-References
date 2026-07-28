---
title: GetByteCount()
second_title: Aspose.Slides C++ API Referencia
description: A karakterpuffer kódolásához szükséges karakterek számának lekérése.
type: docs
weight: 235
url: /hu/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metódus


A karakterpuffer kódolásához szükséges karakterek számának lekérése.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakterpuffer. |
| index | int | Szelet kezdete. |
| count | int | Szelet mérete. |

### Visszatérési érték

Szükséges pufferméret.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metódus


A karakterpuffer kódolásához szükséges karakterek számának lekérése.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Karakterpuffer. |
| index | int | Szelet kezdete. |
| count | int | Szelet mérete. |

### Visszatérési érték

Szükséges pufferméret.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metódus


A karakterpuffer kódolásához szükséges karakterek számának lekérése.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Karakterpuffer. |
| index | int | Szelet kezdete. |
| count | int | Szelet mérete. |

### Visszatérési érték

Szükséges pufferméret.

## Encoding::GetByteCount(const String\&) metódus


Egy karakterlánc kódolásához szükséges karakterek számának lekérése.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) kódoláshoz. |

### Visszatérési érték

Szükséges pufferméret.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) metódus


A karakterpuffer kódolásához szükséges karakterek számának lekérése.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakterpuffer. |

### Visszatérési érték

Szükséges pufferméret.

## Encoding::GetByteCount(const char_t *, int) metódus


A karakterpuffer kódolásához szükséges karakterek számának lekérése.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Karakterpuffer. |
| count | int | [Buffer](../../../system/buffer/) mérete. |

### Visszatérési érték

Szükséges pufferméret.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)