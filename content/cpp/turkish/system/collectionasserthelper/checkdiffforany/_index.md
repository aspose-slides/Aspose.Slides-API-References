---
title: CheckDiffForAny()
second_title: Aspose.Slides for C++ API Referansı
description: Herhangi bir koleksiyon öğesinin koşulu sağladığını denetler.
type: docs
weight: 27
url: /tr/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) metot

Herhangi bir koleksiyon öğesinin koşulu sağladığını denetler.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Kontrol edilecek koşul. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Kontrol edilecek değerler. |

### Dönüş Değeri

Herhangi bir öğe için kontrol başarılıysa true, tümü geçerse false.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../sharedptr/)
* Sınıf [ICollection](../../../system.collections.generic/icollection/)
* Yapı [CollectionAssertHelper](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)