---
title: MakeDiff()
second_title: Aspose.Slides for C++ API Referansı
description: İki koleksiyon arasındaki 'diff' değerini hesaplar. Her bir koleksiyonun her öğesi anahtar olarak alındığında, sonuç değeri \"expected\" koleksiyonunda öğe daha fazla kez bulunuyorsa pozitif, \"actual\" koleksiyonunda daha fazla kez bulunuyorsa negatif ve her iki koleksiyonda da öğe aynı sayıda bulunuyorsa sıfır olur.
type: docs
weight: 1
url: /tr/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method

İki koleksiyon arasındaki 'diff' değerini hesaplar. Her bir koleksiyonun her öğesi anahtar olarak alındığında, sonuç değeri \"expected\" koleksiyonunda öğe daha fazla kez bulunuyorsa pozitif, \"actual\" koleksiyonunda daha fazla kez bulunuyorsa negatif ve her iki koleksiyonda da öğe eşit sayıda bulunuyorsa sıfır olur.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Beklenen koleksiyon öğe tipi. |
| T2 | Gerçek koleksiyon öğe tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Beklenen koleksiyon. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Gerçek koleksiyon. |

### Dönüş Değeri

Yukarıdaki kurallara göre, değer bazında karşılaştırma sonuçlarını içeren harita.

## İlgili

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Dictionary](../../../system.collections.generic/dictionary/)
* Sınıf [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)