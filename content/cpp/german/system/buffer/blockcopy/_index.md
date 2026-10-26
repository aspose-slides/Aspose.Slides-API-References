---
title: BlockCopy()
second_title: Aspose.Slides für C++ API Referenz
description: Kopiert eine angegebene Anzahl von Bytes vom Quellpuffer in den Zielpuffer.
type: docs
weight: 1
url: /de/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) Methode


Kopiert eine angegebene Anzahl von Bytes vom Quellpuffer in den Zielpuffer.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const **uint8_t** * | Zeiger auf den Quellpuffer |
| srcOffset | int | Ein Byte-Offset im Quellpuffer, an dem das Kopieren beginnt |
| dst | **uint8_t** * | Zeiger auf den Zielpuffer |
| dstOffset | int | Ein Byte-Offset im Zielpuffer, an dem das Einfügen von Daten beginnt |
| count | int | Die Anzahl der zu kopierenden Bytes |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) Methode


Interpretieren zwei angegebene typisierte Arrays als rohe Byte-Arrays und kopieren Daten von einem zum anderen.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TSrc | Der Typ der Elemente des Quellarrays |
| TDst | Der Typ der Elemente des Zielarrays |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Das Quellarray |
| srcOffset | int | Ein Byte-Offset im Quellarray, an dem das Kopieren beginnt |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Das Zielarray |
| dstOffset | int | Ein Byte-Offset im Zielarray, an dem das Einfügen von Daten beginnt |
| count | int | Die Anzahl der zu kopierenden Bytes |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) Methode


Interpretieren zwei angegebene Arrays als rohe Byte-Arrays und kopieren Daten von einem zum anderen.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Das Quellarray |
| srcOffset | int | Ein Byte-Offset im Quellarray, an dem das Kopieren beginnt |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Das Zielarray |
| dstOffset | int | Ein Byte-Offset im Zielarray, an dem das Einfügen von Daten beginnt |
| count | int | Die Anzahl der zu kopierenden Bytes |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) Methode


Interpretieren zwei angegebene typisierte Arrays als rohe Byte-Arrays und kopieren Daten von einem zum anderen.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TSrc | Der Typ der Elemente der Quell-Array-Ansicht |
| TDst | Der Typ der Elemente der Ziel-Array-Ansicht |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Die Quell-Array-Ansicht |
| srcOffset | int | Ein Byte-Offset in der Quell-Array-Ansicht, an dem das Kopieren beginnt |
| dst | const System::Details::ArrayView\<TDst\>\& | Die Ziel-Array-Ansicht |
| dstOffset | int | Ein Byte-Offset in der Ziel-Array-Ansicht, an dem das Einfügen von Daten beginnt |
| count | int | Die Anzahl der zu kopierenden Bytes |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) Methode


Interpretieren zwei angegebene typisierte Arrays als rohe Byte-Arrays und kopieren Daten von einem zum anderen.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TSrc | Der Typ der Elemente des Quellarrays |
| TDst | Der Typ der Elemente der Ziel-Array-Ansicht |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Das Quellarray |
| srcOffset | int | Ein Byte-Offset im Quellarray, an dem das Kopieren beginnt |
| dst | const System::Details::ArrayView\<TDst\>\& | Die Ziel-Array-Ansicht |
| dstOffset | int | Ein Byte-Offset in der Ziel-Array-Ansicht, an dem das Einfügen von Daten beginnt |
| count | int | Die Anzahl der zu kopierenden Bytes |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) Methode


Interpretieren zwei angegebene typisierte Arrays als rohe Byte-Arrays und kopieren Daten von einem zum anderen.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TSrc | Der Typ der Elemente der Quell-Array-Ansicht |
| TDst | Der Typ der Elemente des Zielarrays |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Die Quell-Array-Ansicht |
| srcOffset | int | Ein Byte-Offset in der Quell-Array-Ansicht, an dem das Kopieren beginnt |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Das Zielarray |
| dstOffset | int | Ein Byte-Offset im Zielarray, an dem das Einfügen von Daten beginnt |
| count | int | Die Anzahl der zu kopierenden Bytes |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) Methode


Interpretieren zwei angegebene typisierte Arrays als rohe Byte-Arrays und kopieren Daten von einem zum anderen.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TSrc | Der Typ der Elemente des Quell-Stack-Arrays |
| NS | Die Größe des Quell-Stack-Arrays |
| TDst | Der Typ der Elemente des Ziel-Stack-Arrays |
| ND | Die Größe des Ziel-Stack-Arrays |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Das Quell-Stack-Array |
| srcOffset | int | Ein Byte-Offset im Quell-Stack-Array, an dem das Kopieren beginnt |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Das Ziel-Stack-Array |
| dstOffset | int | Ein Byte-Offset im Ziel-Stack-Array, an dem das Einfügen von Daten beginnt |
| count | int | Die Anzahl der zu kopierenden Bytes |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) Methode


Interpretieren zwei angegebene typisierte Arrays als rohe Byte-Arrays und kopieren Daten von einem zum anderen.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TSrc | Der Typ der Elemente des Quellarrays |
| TDst | Der Typ der Elemente des Ziel-Stack-Arrays |
| ND | Die Größe des Ziel-Stack-Arrays |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Das Quellarray |
| srcOffset | int | Ein Byte-Offset im Quellarray, an dem das Kopieren beginnt |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Das Ziel-Stack-Array |
| dstOffset | int | Ein Byte-Offset im Ziel-Stack-Array, an dem das Einfügen von Daten beginnt |
| count | int | Die Anzahl der zu kopierenden Bytes |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) Methode


Interpretieren zwei angegebene typisierte Arrays als rohe Byte-Arrays und kopieren Daten von einem zum anderen.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TSrc | Der Typ der Elemente des Quell-Stack-Arrays |
| NS | Die Größe des Quell-Stack-Arrays |
| TDst | Der Typ der Elemente des Zielarrays |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Das Quell-Stack-Array |
| srcOffset | int | Ein Byte-Offset im Quell-Stack-Array, an dem das Kopieren beginnt |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Das Zielarray |
| dstOffset | int | Ein Byte-Offset im Zielarray, an dem das Einfügen von Daten beginnt |
| count | int | Die Anzahl der zu kopierenden Bytes |

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Buffer](../)
* Klasse [Array](../../array/)
* Klasse [ArrayBase](../../arraybase/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)