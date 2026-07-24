---
title: CollectionAssertHelper
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonla ilgili işlemler için Heler API.
type: docs
weight: 1548
url: /tr/system/collectionasserthelper/
---
## CollectionAssertHelper struct

Heler API for collection-related operations.

```cpp
class CollectionAssertHelper
```

## Methods

| Metot | Açıklama |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Tüm koleksiyon öğelerinin koşula uyduğunu kontrol eder. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Herhangi bir koleksiyon öğesinin koşula uyduğunu kontrol eder. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | İki koleksiyonu mesaj temsili için seri hale getirir. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Koleksiyonu öğelerin string temsillerini birleştirerek stringe dönüştürür. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | İki koleksiyon arasındaki 'diff' değerini hesaplar. Her koleksiyonun her öğesi anahtar olarak alındığında, sonuç değeri öğe \"expected\" koleksiyonunda daha fazla kez ortaya çıkıyorsa pozitif, \"actual\" koleksiyonunda daha fazla kez ortaya çıkıyorsa negatif ve her iki koleksiyonda eşit sayıda ortaya çıkıyorsa sıfır olur. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Mesaj metni olarak kullanılacak stringi biçimlendirir. |
## See Also

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)