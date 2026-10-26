---
title: GetByteCount()
second_title: Aspose.Slides for C++ API Referencia
description: Megkapja a karakterpuffer kódolásához szükséges karakterek számát.
type: docs
weight: 157
url: /hu/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) metódus

Megkapja a karakterpuffer kódolásához szükséges karakterek számát.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | Karakterpuffer. |
| count | int | [Buffer](../../../system/buffer/) méret. |

### Visszatérési érték

Szükséges puffer méret.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metódus

Megkapja a karakterpuffer kódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakterpuffer. |
| index | int | Szelet kezdete. |
| count | int | Szelet mérete. |

### Visszatérési érték

Szükséges puffer méret.

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metódus

Megkapja a karakterpuffer kódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Karakterpuffer. |
| index | int | Szelet kezdete. |
| count | int | Szelet mérete. |

### Visszatérési érték

Szükséges puffer méret.

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metódus

Megkapja a karakterpuffer kódolásához szükséges karakterek számát.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Karakterpuffer. |
| index | int | Szelet kezdete. |
| count | int | Szelet mérete. |

### Visszatérési érték

Szükséges puffer méret.

## UTF7Encoding::GetByteCount(const String\&) metódus

Megkapja a karakterlánc kódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) a kódoláshoz. |

### Visszatérési érték

Szükséges puffer méret.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) metódus

Megkapja a karakterpuffer kódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakterpuffer. |

### Visszatérési érték

Szükséges puffer méret.

## UTF7Encoding::GetByteCount(const char_t *, int) metódus

Megkapja a karakterpuffer kódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | Karakterpuffer. |
| count | int | [Buffer](../../../system/buffer/) méret. |

### Visszatérési érték

Szükséges puffer méret.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [UTF7Encoding](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Text](../../)
* Library [Aspose.Slides](../../../)