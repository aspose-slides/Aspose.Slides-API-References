---
title: SetByte()
second_title: Aspose.Slides för C++ API-referens
description: Tolkar den angivna typade arrayen som en rå byte-array och sätter det angivna bytevärdet vid den angivna byteoffseten.
type: docs
weight: 40
url: /sv/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) metod

Tolkar den angivna typade arrayen som en rå byte-array och sätter det angivna bytevärdet vid den angivna byteoffseten.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Målarrayen |
| index | int | Nollbaserat offset för den byte som ska sättas |
| value | **uint8_t** | Bytevärdet att sätta |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) metod

Tolkar den angivna typade arrayen som en rå byte-array och sätter det angivna bytevärdet vid den angivna byteoffseten.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Målarrayvyn |
| index | int | Nollbaserat offset för den byte som ska sättas |
| value | **uint8_t** | Bytevärdet att sätta |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) metod

Tolkar den angivna typade arrayen som en rå byte-array och sätter det angivna bytevärdet vid den angivna byteoffseten.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i arrayen |
| N | Storleken på stack-arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Målstackarrayen |
| index | int | Nollbaserat offset för den byte som ska sättas |
| value | **uint8_t** | Bytevärdet att sätta |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [Array](../../array/)
* Klass [Buffer](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)