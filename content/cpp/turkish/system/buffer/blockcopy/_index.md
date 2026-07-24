---
title: BlockCopy()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayıda baytı kaynak tampondan hedef tampona kopyalar.
type: docs
weight: 1
url: /tr/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) metod

Belirtilen sayıda baytı kaynak tampondan hedef tamponuna kopyalar.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const **uint8_t** * | Kaynak tamponun işaretçisi |
| srcOffset | int | Kaynak tamponda kopyalamanın başladığı bayt ofseti |
| dst | **uint8_t** * | Hedef tamponun işaretçisi |
| dstOffset | int | Hedef tamponda verinin eklenmeye başlanacağı bayt ofseti |
| count | int | Kopyalanacak bayt sayısı |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metod

Belirtilen iki tiplenmiş diziyi ham bayt dizileri olarak yorumlar ve birinden diğerine veriyi kopyalar.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TSrc | Kaynak dizinin eleman tipi |
| TDst | Hedef dizinin eleman tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Kaynak dizi |
| srcOffset | int | Kaynak dizide kopyalamanın başladığı bayt ofseti |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Hedef dizi |
| dstOffset | int | Hedef dizide verinin eklenmeye başlanacağı bayt ofseti |
| count | int | Kopyalanacak bayt sayısı |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) metod

Belirtilen iki diziyi ham bayt dizileri olarak yorumlar ve birinden diğerine veriyi kopyalar.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Kaynak dizi |
| srcOffset | int | Kaynak dizide kopyalamanın başladığı bayt ofseti |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Hedef dizi |
| dstOffset | int | Hedef dizide verinin eklenmeye başlanacağı bayt ofseti |
| count | int | Kopyalanacak bayt sayısı |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metod

Belirtilen iki tiplenmiş diziyi ham bayt dizileri olarak yorumlar ve birinden diğerine veriyi kopyalar.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TSrc | Kaynak dizi görünümünün eleman tipi |
| TDst | Hedef dizi görünümünün eleman tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Kaynak dizi görünümü |
| srcOffset | int | Kaynak dizi görünümünde kopyalamanın başladığı bayt ofseti |
| dst | const System::Details::ArrayView\<TDst\>\& | Hedef dizi görünümü |
| dstOffset | int | Hedef dizi görünümünde verinin eklenmeye başlanacağı bayt ofseti |
| count | int | Kopyalanacak bayt sayısı |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metod

Belirtilen iki tiplenmiş diziyi ham bayt dizileri olarak yorumlar ve birinden diğerine veriyi kopyalar.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TSrc | Kaynak dizinin eleman tipi |
| TDst | Hedef dizi görünümünün eleman tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Kaynak dizi |
| srcOffset | int | Kaynak dizide kopyalamanın başladığı bayt ofseti |
| dst | const System::Details::ArrayView\<TDst\>\& | Hedef dizi görünümü |
| dstOffset | int | Hedef dizi görünümünde verinin eklenmeye başlanacağı bayt ofseti |
| count | int | Kopyalanacak bayt sayısı |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metod

Belirtilen iki tiplenmiş diziyi ham bayt dizileri olarak yorumlar ve birinden diğerine veriyi kopyalar.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TSrc | Kaynak dizi görünümünün eleman tipi |
| TDst | Hedef dizinin eleman tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Kaynak dizi görünümü |
| srcOffset | int | Kaynak dizi görünümünde kopyalamanın başladığı bayt ofseti |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Hedef dizi |
| dstOffset | int | Hedef dizide verinin eklenmeye başlanacağı bayt ofseti |
| count | int | Kopyalanacak bayt sayısı |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metod

Belirtilen iki tiplenmiş diziyi ham bayt dizileri olarak yorumlar ve birinden diğerine veriyi kopyalar.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TSrc | Kaynak yığın dizisinin eleman tipi |
| NS | Kaynak yığın dizisinin boyutu |
| TDst | Hedef yığın dizisinin eleman tipi |
| ND | Hedef yığın dizisinin boyutu |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Kaynak yığın dizisi |
| srcOffset | int | Kaynak yığın dizisinde kopyalamanın başladığı bayt ofseti |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Hedef yığın dizisi |
| dstOffset | int | Hedef yığın dizisinde verinin eklenmeye başlanacağı bayt ofseti |
| count | int | Kopyalanacak bayt sayısı |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metod

Belirtilen iki tiplenmiş diziyi ham bayt dizileri olarak yorumlar ve birinden diğerine veriyi kopyalar.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TSrc | Kaynak dizinin eleman tipi |
| TDst | Hedef yığın dizisinin eleman tipi |
| ND | Hedef yığın dizisinin boyutu |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Kaynak dizi |
| srcOffset | int | Kaynak dizide kopyalamanın başladığı bayt ofseti |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Hedef yığın dizisi |
| dstOffset | int | Hedef yığın dizisinde verinin eklenmeye başlanacağı bayt ofseti |
| count | int | Kopyalanacak bayt sayısı |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metod

Belirtilen iki tiplenmiş diziyi ham bayt dizileri olarak yorumlar ve birinden diğerine veriyi kopyalar.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TSrc | Kaynak yığın dizisinin eleman tipi |
| NS | Kaynak yığın dizisinin boyutu |
| TDst | Hedef dizinin eleman tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Kaynak yığın dizisi |
| srcOffset | int | Kaynak yığın dizisinde kopyalamanın başladığı bayt ofseti |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Hedef dizi |
| dstOffset | int | Hedef dizide verinin eklenmeye başlanacağı bayt ofseti |
| count | int | Kopyalanacak bayt sayısı |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Buffer](../)
* Sınıf [Array](../../array/)
* Sınıf [ArrayBase](../../arraybase/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)