---
title: Copy()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayıda öğeyi kaynak diziden hedef diziye kopyalar.
type: docs
weight: 729
url: /tr/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) metod

Belirtilen sayıda öğeyi kaynak diziden hedef diziye kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Kaynak dizi |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Hedef dizi |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) metod

Belirtilen sayıda öğeyi kaynak dizi görünümünden hedef diziye kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Kaynak dizi görünümü |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Hedef dizi |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) metod

Belirtilen sayıda öğeyi kaynak diziden hedef dizi görünümüne kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Kaynak dizi |
| dstArray | System::Details::ArrayView\<DstType\> | Hedef dizi görünümü |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) metod

Belirtilen sayıda öğeyi kaynak dizi görünümünden hedef dizi görünümüne kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Kaynak dizi görünümü |
| dstArray | System::Details::ArrayView\<DstType\> | Hedef dizi görünümü |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) metod

Belirtilen sayıda öğeyi yığın üzerindeki kaynak diziden hedef diziye kopyalar.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Yığın üzerindeki kaynak dizi |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Hedef dizi |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) metod

Belirtilen sayıda öğeyi kaynak diziden yığın üzerindeki hedef diziye kopyalar.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Kaynak dizi |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Yığın üzerindeki hedef dizi |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) metod

Belirtilen sayıda öğeyi yığın üzerindeki kaynak diziden yığın üzerindeki hedef diziye kopyalar.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Yığın üzerindeki kaynak dizi |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Yığın üzerindeki hedef dizi |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metod

Belirtilen sayıda öğeyi kaynak dizide belirtilen konumdan başlayarak hedef dizide belirtilen konuma kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizi öğelerinin türü |
| DstType | Hedef dizi öğelerinin türü |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Kaynak dizi |
| srcIndex | **int64_t** | [Index](../../index/) kaynak dizide kopyalanacak öğeler aralığının başlangıcını belirten indeks |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Hedef dizi |
| dstIndex | **int64_t** | [Index](../../index/) hedef dizide kopyalanan öğelerin eklenmeye başlanacağı konum |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metod

Belirtilen sayıda öğeyi kaynak dizi görünümünde belirtilen konumdan başlayarak hedef dizide belirtilen konuma kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizi görünümündeki öğelerin türü |
| DstType | Hedef dizi öğelerinin türü |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Kaynak dizi görünümü |
| srcIndex | **int64_t** | [Index](../../index/) kaynak dizi görünümünde kopyalanacak öğeler aralığının başlangıcını belirten indeks |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Hedef dizi |
| dstIndex | **int64_t** | [Index](../../index/) hedef dizide kopyalanan öğelerin eklenmeye başlanacağı konum |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) metod

Belirtilen sayıda öğeyi kaynak dizide belirtilen konumdan başlayarak hedef dizi görünümünde belirtilen konuma kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizi öğelerinin türü |
| DstType | Hedef dizi görünümündeki öğelerin türü |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Kaynak dizi |
| srcIndex | **int64_t** | [Index](../../index/) kaynak dizide kopyalanacak öğeler aralığının başlangıcını belirten indeks |
| dstArray | System::Details::ArrayView\<DstType\> | Hedef dizi görünümü |
| dstIndex | **int64_t** | [Index](../../index/) hedef dizi görünümünde kopyalanan öğelerin eklenmeye başlanacağı konum |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) metod

Belirtilen sayıda öğeyi kaynak dizi görünümünde belirtilen konumdan başlayarak hedef dizi görünümünde belirtilen konuma kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizi görünümündeki öğelerin türü |
| DstType | Hedef dizi görünümündeki öğelerin türü |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Kaynak dizi görünümü |
| srcIndex | **int64_t** | [Index](../../index/) kaynak dizi görünümünde kopyalanacak öğeler aralığının başlangıcını belirten indeks |
| dstArray | System::Details::ArrayView\<DstType\> | Hedef dizi görünümü |
| dstIndex | **int64_t** | [Index](../../index/) hedef dizi görünümünde kopyalanan öğelerin eklenmeye başlanacağı konum |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metod

Belirtilen sayıda öğeyi yığın üzerindeki kaynak dizide belirtilen konumdan başlayarak hedef diziye kopyalar.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| SrcType | Yığın üzerindeki kaynak dizi öğelerinin türü |
| DstType | Hedef dizi öğelerinin türü |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Yığın üzerindeki kaynak dizi |
| srcIndex | **int64_t** | [Index](../../index/) yığın üzerindeki kaynak dizide kopyalanacak öğeler aralığının başlangıcını belirten indeks |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Hedef dizi |
| dstIndex | **int64_t** | [Index](../../index/) hedef dizide kopyalanan öğelerin eklenmeye başlanacağı konum |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) metod

Belirtilen sayıda öğeyi kaynak dizide belirtilen konumdan başlayarak yığın üzerindeki hedef diziye kopyalar.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizi öğelerinin türü |
| DstType | Yığın üzerindeki hedef dizi öğelerinin türü |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Kaynak dizi |
| srcIndex | **int64_t** | [Index](../../index/) kaynak dizide kopyalanacak öğeler aralığının başlangıcını belirten indeks |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Yığın üzerindeki hedef dizi |
| dstIndex | **int64_t** | [Index](../../index/) yığın üzerindeki hedef dizide kopyalanan öğelerin eklenmeye başlanacağı konum |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) metod

Belirtilen sayıda öğeyi yığın üzerindeki kaynak dizide belirtilen konumdan başlayarak yığın üzerindeki hedef dizide belirtilen konuma kopyalar.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| SrcType | Yığın üzerindeki kaynak dizi öğelerinin türü |
| DstType | Yığın üzerindeki hedef dizi öğelerinin türü |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Yığın üzerindeki kaynak dizi |
| srcIndex | **int64_t** | [Index](../../index/) yığın üzerindeki kaynak dizide kopyalanacak öğeler aralığının başlangıcını belirten indeks |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Yığın üzerindeki hedef dizi |
| dstIndex | **int64_t** | [Index](../../index/) yığın üzerindeki hedef dizide kopyalanan öğelerin eklenmeye başlanacağı konum |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) metod

Belirtilen sayıda öğeyi kaynak dizi görünümünde belirtilen konumdan başlayarak yığın üzerindeki hedef dizide belirtilen konuma kopyalar.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| SrcType | Yığın üzerindeki kaynak dizi görünümündeki öğelerin türü |
| DstType | Yığın üzerindeki hedef dizi öğelerinin türü |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Kaynak dizi görünümü |
| srcIndex | **int64_t** | [Index](../../index/) kaynak dizi görünümünde kopyalanacak öğeler aralığının başlangıcını belirten indeks |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Yığın üzerindeki hedef dizi |
| dstIndex | **int64_t** | [Index](../../index/) yığın üzerindeki hedef dizide kopyalanan öğelerin eklenmeye başlanacağı konum |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [Array](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)