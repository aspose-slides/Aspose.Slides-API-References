---
title: ByteLength()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer antalet byte som upptas av alla element i den angivna arrayen.
type: docs
weight: 14
url: /sv/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) method

Bestämmer antalet byte som upptas av alla element i den angivna arrayen.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | En array |

### Returvärde

Antalet byte som upptas av alla element i den angivna arrayen

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) method

Bestämmer antalet byte som upptas av alla element i den angivna arrayen.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i arrayvyn |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | En arrayvy |

### Returvärde

Antalet byte som upptas av alla element i den angivna arrayvyn

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) method

Bestämmer antalet byte som upptas av alla element i den angivna arrayen.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i stackarrayen |
| N | Storleken på stackarrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | En stackarray |

### Returvärde

Antalet byte som upptas av alla element i den angivna stackarrayen

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)