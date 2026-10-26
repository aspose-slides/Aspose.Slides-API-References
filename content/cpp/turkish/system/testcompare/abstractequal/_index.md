---
title: AbstractEqual()
second_title: Aspose.Slides C++ için API Referansı
description: Bilinmeyen türdeki iki koleksiyonu karşılaştırır.
type: docs
weight: 14
url: /tr/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) metot

Bilinmeyen türdeki iki koleksiyonu karşılaştırır.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Koleksiyon öğesi tipi. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Sol taraf koleksiyonu. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Sağ taraf koleksiyonu. |

### Dönüş Değeri

true eğer koleksiyonlar eşleşiyorsa (örn. ikisi de null), ya da boyutlar eşleşiyorsa ve öğeler eşleşiyorsa, aksi takdirde false.

## İlgili

* Sınıf [ICollection](../../../system.collections.generic/icollection/)
* Yapı [TestCompare](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)