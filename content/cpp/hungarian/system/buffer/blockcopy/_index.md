---
title: BlockCopy()
second_title: Aspose.Slides for C++ API Referenciája
description: Másolja a megadott számú bájtot a forrás pufforból a cél pufforba.
type: docs
weight: 1
url: /hu/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) metódus

Másolja a megadott számú bájtot a forrás pufforból a cél pufforba.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const **uint8_t** * | Mutató a forrás pufforra |
| srcOffset | int | Byte eltolás a forrás pufforban, ahol a másolás kezdődik |
| dst | **uint8_t** * | Mutató a cél pufforra |
| dstOffset | int | Byte eltolás a cél pufforban, ahol az adatok beszúrása kezdődik |
| count | int | A másolandó bájtok száma |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metódus

Két megadott típusú tömböt értelmez nyers bájt tömbként, és adatot másol az egyikről a másikra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TSrc | A forrás tömb elemének típusa |
| TDst | A cél tömb elemének típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | A forrás tömb |
| srcOffset | int | Byte eltolás a forrás tömbben, ahol a másolás kezdődik |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | A cél tömb |
| dstOffset | int | Byte eltolás a cél tömbben, ahol az adatok beszúrása kezdődik |
| count | int | A másolandó bájtok száma |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) metódus

Két megadott tömböt értelmez nyers bájt tömbként, és adatot másol az egyikről a másikra.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | A forrás tömb |
| srcOffset | int | Byte eltolás a forrás tömbben, ahol a másolás kezdődik |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | A cél tömb |
| dstOffset | int | Byte eltolás a cél tömbben, ahol az adatok beszúrása kezdődik |
| count | int | A másolandó bájtok száma |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metódus

Két megadott típusú tömbnézetet értelmez nyers bájt tömbként, és adatot másol az egyikről a másikra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TSrc | A forrás tömbnézet elemének típusa |
| TDst | A cél tömbnézet elemének típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | A forrás tömbnézet |
| srcOffset | int | Byte eltolás a forrás tömbnézetben, ahol a másolás kezdődik |
| dst | const System::Details::ArrayView\<TDst\>\& | A cél tömbnézet |
| dstOffset | int | Byte eltolás a cél tömbnézetben, ahol az adatok beszúrása kezdődik |
| count | int | A másolandó bájtok száma |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metódus

Két megadott típusú tömböt értelmez nyers bájt tömbként, és adatot másol az egyikről a másikra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TSrc | A forrás tömb elemének típusa |
| TDst | A cél tömbnézet elemének típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | A forrás tömb |
| srcOffset | int | Byte eltolás a forrás tömbben, ahol a másolás kezdődik |
| dst | const System::Details::ArrayView\<TDst\>\& | A cél tömbnézet |
| dstOffset | int | Byte eltolás a cél tömbnézetben, ahol az adatok beszúrása kezdődik |
| count | int | A másolandó bájtok száma |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metódus

Két megadott típusú tömbnézetet értelmez nyers bájt tömbként, és adatot másol az egyikről a másikra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TSrc | A forrás tömbnézet elemének típusa |
| TDst | A cél tömb elemének típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | A forrás tömbnézet |
| srcOffset | int | Byte eltolás a forrás tömbnézetben, ahol a másolás kezdődik |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | A cél tömb |
| dstOffset | int | Byte eltolás a cél tömbben, ahol az adatok beszúrása kezdődik |
| count | int | A másolandó bájtok száma |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metódus

Két megadott típusú veremtömböt értelmez nyers bájt tömbként, és adatot másol az egyikről a másikra.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TSrc | A forrás veremtömb elemének típusa |
| NS | A forrás veremtömb mérete |
| TDst | A cél veremtömb elemének típusa |
| ND | A cél veremtömb mérete |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | A forrás veremtömb |
| srcOffset | int | Byte eltolás a forrás veremtömbben, ahol a másolás kezdődik |
| dst | const System::Details::StackArray\<TDst, ND\>\& | A cél veremtömb |
| dstOffset | int | Byte eltolás a cél veremtömbben, ahol az adatok beszúrása kezdődik |
| count | int | A másolandó bájtok száma |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metódus

Két megadott típusú tömböt és veremtömböt értelmez nyers bájt tömbként, és adatot másol az egyikről a másikra.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TSrc | A forrás tömb elemének típusa |
| TDst | A cél veremtömb elemének típusa |
| ND | A cél veremtömb mérete |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | A forrás tömb |
| srcOffset | int | Byte eltolás a forrás tömbben, ahol a másolás kezdődik |
| dst | const System::Details::StackArray\<TDst, ND\>\& | A cél veremtömb |
| dstOffset | int | Byte eltolás a cél veremtömbben, ahol az adatok beszúrása kezdődik |
| count | int | A másolandó bájtok száma |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metódus

Két megadott típusú veremtömböt és tömböt értelmez nyers bájt tömbként, és adatot másol az egyikről a másikra.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TSrc | A forrás veremtömb elemének típusa |
| NS | A forrás veremtömb mérete |
| TDst | A cél tömb elemének típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | A forrás veremtömb |
| srcOffset | int | Byte eltolás a forrás veremtömbben, ahol a másolás kezdődik |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | A cél tömb |
| dstOffset | int | Byte eltolás a cél tömbben, ahol az adatok beszúrása kezdődik |
| count | int | A másolandó bájtok száma |

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Class [Buffer](../)
* Class [Array](../../array/)
* Class [ArrayBase](../../arraybase/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)