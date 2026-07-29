---
title: GetByte()
second_title: Aspose.Slides för C++ API-referens
description: Tolkar den specificerade typade arrayen som en råbytearray och hämtar bytevärdet vid angivet byteoffset.
type: docs
weight: 27
url: /sv/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr<Array<T>>&, int) metod


Tolkar den specificerade typade arrayen som en råbytearray och hämtar bytevärdet vid angivet byteoffset.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)<[Array](../../array/)<T>> & | Målarrayen |
| index | int | Nollbaserat offset för den byte som ska hämtas |

### Returvärde

Bytevärdet på det angivna indexet

## Buffer::GetByte(const System::Details::ArrayView<T>&, int) metod


Tolkar den specificerade typade arrayen som en råbytearray och hämtar bytevärdet vid angivet byteoffset.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i arrayvyn |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const System::Details::ArrayView<T> & | Målarrayvyn |
| index | int | Nollbaserat offset för den byte som ska hämtas |

### Returvärde

Bytevärdet på det angivna indexet

## Buffer::GetByte(const System::Details::StackArray<T, N>&, int) metod


Tolkar den specificerade typade arrayen som en råbytearray och hämtar bytevärdet vid angivet byteoffset.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i stackarrayen |
| N | Storleken på stackarrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const System::Details::StackArray<T, N> & | Målstackarrayen |
| index | int | Nollbaserat offset för den byte som ska hämtas |

### Returvärde

Bytevärdet på det angivna indexet

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [Array](../../array/)
* Klass [Buffer](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)