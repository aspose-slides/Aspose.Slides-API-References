---
title: BlockCopy()
second_title: Reference API Aspose.Slides pro C++
description: Zkopíruje určený počet bajtů ze zdrojového bufferu do cílového bufferu.
type: docs
weight: 1
url: /cs/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) metoda


Zkopíruje určený počet bajtů ze zdrojového bufferu do cílového bufferu.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const **uint8_t** * | Ukazatel na zdrojový buffer |
| srcOffset | int | Posun v bajtech ve zdrojovém bufferu, kde začíná kopírování |
| dst | **uint8_t** * | Ukazatel na cílový buffer |
| dstOffset | int | Posun v bajtech v cílovém bufferu, kde se má začít vkládat data |
| count | int | Počet bajtů k zkopírování |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metoda


Interpretuje dva určené typové pole jako surové pole bajtů a kopíruje data z jednoho do druhého.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TSrc | Typ prvků zdrojového pole |
| TDst | Typ prvků cílového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Zdrojové pole |
| srcOffset | int | Posun v bajtech ve zdrojovém poli, kde začíná kopírování |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Cílové pole |
| dstOffset | int | Posun v bajtech v cílovém poli, kde se má začít vkládat data |
| count | int | Počet bajtů k zkopírování |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) metoda


Interpretuje dva určená pole jako surové pole bajtů a kopíruje data z jednoho do druhého.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Zdrojové pole |
| srcOffset | int | Posun v bajtech ve zdrojovém poli, kde začíná kopírování |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Cílové pole |
| dstOffset | int | Posun v bajtech v cílovém poli, kde se má začít vkládat data |
| count | int | Počet bajtů k zkopírování |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metoda


Interpretuje dva určené typové pole jako surové pole bajtů a kopíruje data z jednoho do druhého.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TSrc | Typ prvků zdrojového pohledu pole |
| TDst | Typ prvků cílového pohledu pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Zdrojový pohled pole |
| srcOffset | int | Posun v bajtech ve zdrojovém pohledu pole, kde začíná kopírování |
| dst | const System::Details::ArrayView\<TDst\>\& | Cílový pohled pole |
| dstOffset | int | Posun v bajtech v cílovém pohledu pole, kde se má začít vkládat data |
| count | int | Počet bajtů k zkopírování |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metoda


Interpretuje dva určené typové pole jako surové pole bajtů a kopíruje data z jednoho do druhého.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TSrc | Typ prvků zdrojového pole |
| TDst | Typ prvků cílového pohledu pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Zdrojové pole |
| srcOffset | int | Posun v bajtech ve zdrojovém poli, kde začíná kopírování |
| dst | const System::Details::ArrayView\<TDst\>\& | Cílový pohled pole |
| dstOffset | int | Posun v bajtech v cílovém pohledu pole, kde se má začít vkládat data |
| count | int | Počet bajtů k zkopírování |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metoda


Interpretuje dva určené typové pole jako surové pole bajtů a kopíruje data z jednoho do druhého.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TSrc | Typ prvků zdrojového pohledu pole |
| TDst | Typ prvků cílového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Zdrojový pohled pole |
| srcOffset | int | Posun v bajtech ve zdrojovém pohledu pole, kde začíná kopírování |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Cílové pole |
| dstOffset | int | Posun v bajtech v cílovém poli, kde se má začít vkládat data |
| count | int | Počet bajtů k zkopírování |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metoda


Interpretuje dva určené typové zásobníkové pole jako surové pole bajtů a kopíruje data z jednoho do druhého.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TSrc | Typ prvků zdrojového zásobníkového pole |
| NS | Velikost zdrojového zásobníkového pole |
| TDst | Typ prvků cílového zásobníkového pole |
| ND | Velikost cílového zásobníkového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Zdrojové zásobníkové pole |
| srcOffset | int | Posun v bajtech ve zdrojovém zásobníkovém poli, kde začíná kopírování |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Cílové zásobníkové pole |
| dstOffset | int | Posun v bajtech v cílovém zásobníkovém poli, kde se má začít vkládat data |
| count | int | Počet bajtů k zkopírování |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metoda


Interpretuje dva určené typové pole jako surové pole bajtů a kopíruje data z jednoho do druhého.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TSrc | Typ prvků zdrojového pole |
| TDst | Typ prvků cílového zásobníkového pole |
| ND | Velikost cílového zásobníkového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Zdrojové pole |
| srcOffset | int | Posun v bajtech ve zdrojovém poli, kde začíná kopírování |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Cílové zásobníkové pole |
| dstOffset | int | Posun v bajtech v cílovém zásobníkovém poli, kde se má začít vkládat data |
| count | int | Počet bajtů k zkopírování |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metoda


Interpretuje dva určené typové zásobníkové pole jako surové pole bajtů a kopíruje data z jednoho do druhého.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TSrc | Typ prvků zdrojového zásobníkového pole |
| NS | Velikost zdrojového zásobníkového pole |
| TDst | Typ prvků cílového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Zdrojové zásobníkové pole |
| srcOffset | int | Posun v bajtech ve zdrojovém zásobníkovém poli, kde začíná kopírování |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Cílové pole |
| dstOffset | int | Posun v bajtech v cílovém poli, kde se má začít vkládat data |
| count | int | Počet bajtů k zkopírování |

## Viz také

* Definice typu [SharedPtr](../../sharedptr/)
* Třída [Buffer](../)
* Třída [Array](../../array/)
* Třída [ArrayBase](../../arraybase/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)