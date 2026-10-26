---
title: BlockCopy()
second_title: Aspose.Slides för C++ API-referens
description: Kopierar ett specificerat antal byte från källbufferten till destinationsbufferten.
type: docs
weight: 1
url: /sv/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) method

Kopierar ett specificerat antal byte från källbufferten till destinationsbufferten.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const **uint8_t** * | Pekare till källbufferten |
| srcOffset | int | En byteförskjutning i källbufferten där kopieringen startar |
| dst | **uint8_t** * | Pekare till destinationsbufferten |
| dstOffset | int | En byteförskjutning i destinationsbufferten där infogning av data startar |
| count | int | Antalet byte som ska kopieras |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) method

Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TSrc | Typen av element i källarrayen |
| TDst | Typen av element i destinationsarrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Källarrayen |
| srcOffset | int | En byteförskjutning i källarrayen där kopieringen startar |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Destinationsarrayen |
| dstOffset | int | En byteförskjutning i destinationsarrayen där infogning av data startar |
| count | int | Antalet byte som ska kopieras |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) method

Tolkar två specificerade arrayer som råa byte-arrayer och kopierar data från den ena till den andra.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Källarrayen |
| srcOffset | int | En byteförskjutning i källarrayen där kopieringen startar |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Destinationsarrayen |
| dstOffset | int | En byteförskjutning i destinationsarrayen där infogning av data startar |
| count | int | Antalet byte som ska kopieras |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) method

Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TSrc | Typen av element i källarrayvyn |
| TDst | Typen av element i destinationsarrayvyn |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Källarrayvyn |
| srcOffset | int | En byteförskjutning i källarrayvyn där kopieringen startar |
| dst | const System::Details::ArrayView\<TDst\>\& | Destinationsarrayvyn |
| dstOffset | int | En byteförskjutning i destinationsarrayvyn där infogning av data startar |
| count | int | Antalet byte som ska kopieras |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) method

Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TSrc | Typen av element i källarrayen |
| TDst | Typen av element i destinationsarrayvyn |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Källarrayen |
| srcOffset | int | En byteförskjutning i källarrayen där kopieringen startar |
| dst | const System::Details::ArrayView\<TDst\>\& | Destinationsarrayvyn |
| dstOffset | int | En byteförskjutning i destinationsarrayvyn där infogning av data startar |
| count | int | Antalet byte som ska kopieras |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) method

Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TSrc | Typen av element i källarrayvyn |
| TDst | Typen av element i destinationsarrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Källarrayvyn |
| srcOffset | int | En byteförskjutning i källarrayvyn där kopieringen startar |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Destinationsarrayen |
| dstOffset | int | En byteförskjutning i destinationsarrayen där infogning av data startar |
| count | int | Antalet byte som ska kopieras |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) method

Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TSrc | Typen av element i källstackarrayen |
| NS | Storleken på källstackarrayen |
| TDst | Typen av element i destinationsstackarrayen |
| ND | Storleken på destinationsstackarrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Källstackarrayen |
| srcOffset | int | En byteförskjutning i källstackarrayen där kopieringen startar |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Destinationsstackarrayen |
| dstOffset | int | En byteförskjutning i destinationsstackarrayen där infogning av data startar |
| count | int | Antalet byte som ska kopieras |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) method

Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TSrc | Typen av element i källarrayen |
| TDst | Typen av element i destinationsstackarrayen |
| ND | Storleken på destinationsstackarrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Källarrayen |
| srcOffset | int | En byteförskjutning i källarrayen där kopieringen startar |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Destinationsstackarrayen |
| dstOffset | int | En byteförskjutning i destinationsstackarrayen där infogning av data startar |
| count | int | Antalet byte som ska kopieras |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) method

Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TSrc | Typen av element i källstackarrayen |
| NS | Storleken på källstackarrayen |
| TDst | Typen av element i destinationsarrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Källstackarrayen |
| srcOffset | int | En byteförskjutning i källstackarrayen där kopieringen startar |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Destinationsarrayen |
| dstOffset | int | En byteförskjutning i destinationsarrayen där infogning av data startar |
| count | int | Antalet byte som ska kopieras |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [Buffer](../)
* Klass [Array](../../array/)
* Klass [ArrayBase](../../arraybase/)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)