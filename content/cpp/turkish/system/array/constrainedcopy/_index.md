---
title: ConstrainedCopy()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen kaynaktan başlayan bir System.Array'den öğeler aralığını kopyalar.
type: docs
weight: 716
url: /tr/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metot

Belirtilen kaynaktan başlayan bir [System.Array](../)'den öğeler aralığını kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizi içindeki öğelerin türü |
| DstType | Hedef dizi içindeki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Kaynak dizi |
| srcIndex | **int64_t** | [Index](../../index/) kaynak dizide kopyalanacak öğe aralığının başlangıcını belirten |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Hedef dizi |
| dstIndex | **int64_t** | [Index](../../index/) hedef dizide kopyalanan öğelerin eklenmeye başlanacağı konumu belirten |
| count | **int64_t** | Kopyalanacak öğe sayısı |

## Açıklamalar

HERHANGİ BİR TAMAMLAMA YOKSA GEÇİCİ HAM UYGULAMA!

## Ayrıca Bakınız

* Tip tanımı [ArrayPtr](../../arrayptr/)
* Sınıf [Array](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)