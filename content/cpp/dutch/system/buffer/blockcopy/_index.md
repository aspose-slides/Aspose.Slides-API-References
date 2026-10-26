---
title: BlockCopy()
second_title: Aspose.Slides for C++ API-referentie
description: Kopieert een opgegeven aantal bytes van de bronbuffer naar de doelbuffer.
type: docs
weight: 1
url: /nl/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) methode

Kopieert een opgegeven aantal bytes van de bronbuffer naar de doelbuffer.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const **uint8_t** * | Pointer naar de bronbuffer |
| srcOffset | int | Een byteoffset in de bronbuffer waar het kopiëren start |
| dst | **uint8_t** * | Pointer naar de doelbuffer |
| dstOffset | int | Een byteoffset in de doelbuffer waar gegevens worden ingevoegd |
| count | int | Het aantal bytes om te kopiëren |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) methode

Interpreteert twee opgegeven getypeerde arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| TSrc | Het type van de elementen van de bronarray |
| TDst | Het type van de elementen van de doelarray |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | De bronarray |
| srcOffset | int | Een byteoffset in de bronarray waar het kopiëren start |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | De doelarray |
| dstOffset | int | Een byteoffset in de doelarray waar gegevens worden ingevoegd |
| count | int | Het aantal bytes om te kopiëren |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) methode

Interpreteert twee opgegeven arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | De bronarray |
| srcOffset | int | Een byteoffset in de bronarray waar het kopiëren start |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | De doelarray |
| dstOffset | int | Een byteoffset in de doelarray waar gegevens worden ingevoegd |
| count | int | Het aantal bytes om te kopiëren |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) methode

Interpreteert twee opgegeven getypeerde arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| TSrc | Het type van de elementen van de bron-array-view |
| TDst | Het type van de elementen van de doel-array-view |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | De bron-array-view |
| srcOffset | int | Een byteoffset in de bron-array-view waar het kopiëren start |
| dst | const System::Details::ArrayView\<TDst\>\& | De doel-array-view |
| dstOffset | int | Een byteoffset in de doel-array-view waar gegevens worden ingevoegd |
| count | int | Het aantal bytes om te kopiëren |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) methode

Interpreteert twee opgegeven getypeerde arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| TSrc | Het type van de elementen van de bronarray |
| TDst | Het type van de elementen van de doel-array-view |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | De bronarray |
| srcOffset | int | Een byteoffset in de bronarray waar het kopiëren start |
| dst | const System::Details::ArrayView\<TDst\>\& | De doel-array-view |
| dstOffset | int | Een byteoffset in de doel-array-view waar gegevens worden ingevoegd |
| count | int | Het aantal bytes om te kopiëren |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) methode

Interpreteert twee opgegeven getypeerde arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| TSrc | Het type van de elementen van de bron-array-view |
| TDst | Het type van de elementen van de doelarray |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | De bron-array-view |
| srcOffset | int | Een byteoffset in de bron-array-view waar het kopiëren start |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | De doelarray |
| dstOffset | int | Een byteoffset in de doelarray waar gegevens worden ingevoegd |
| count | int | Het aantal bytes om te kopiëren |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) methode

Interpreteert twee opgegeven getypeerde arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| TSrc | Het type van de elementen van de bron-stack-array |
| NS | De grootte van de bron-stack-array |
| TDst | Het type van de elementen van de doel-stack-array |
| ND | De grootte van de doel-stack-array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | De bron-stack-array |
| srcOffset | int | Een byteoffset in de bron-stack-array waar het kopiëren start |
| dst | const System::Details::StackArray\<TDst, ND\>\& | De doel-stack-array |
| dstOffset | int | Een byteoffset in de doel-stack-array waar gegevens worden ingevoegd |
| count | int | Het aantal bytes om te kopiëren |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) methode

Interpreteert twee opgegeven getypeerde arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| TSrc | Het type van de elementen van de bronarray |
| TDst | Het type van de elementen van de doel-stack-array |
| ND | De grootte van de doel-stack-array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | De bronarray |
| srcOffset | int | Een byteoffset in de bronarray waar het kopiëren start |
| dst | const System::Details::StackArray\<TDst, ND\>\& | De doel-stack-array |
| dstOffset | int | Een byteoffset in de doel-stack-array waar gegevens worden ingevoegd |
| count | int | Het aantal bytes om te kopiëren |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) methode

Interpreteert twee opgegeven getypeerde arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| TSrc | Het type van de elementen van de bron-stack-array |
| NS | De grootte van de bron-stack-array |
| TDst | Het type van de elementen van de doelarray |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | De bron-stack-array |
| srcOffset | int | Een byteoffset in de bron-stack-array waar het kopiëren start |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | De doelarray |
| dstOffset | int | Een byteoffset in de doelarray waar gegevens worden ingevoegd |
| count | int | Het aantal bytes om te kopiëren |

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Buffer](../)
* Klasse [Array](../../array/)
* Klasse [ArrayBase](../../arraybase/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)