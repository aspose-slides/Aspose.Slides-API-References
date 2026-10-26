---
title: CheckDiffForAll()
second_title: Aspose.Slides for C++ API Referansı
description: Tüm koleksiyon öğelerinin önermeye uyduğunu kontrol eder.
type: docs
weight: 14
url: /tr/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) metodu

Tüm koleksiyon öğelerinin önermeye uyduğunu kontrol eder.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Kontrol edilecek önermedir. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Kontrol edilecek değerler. |

### Dönüş Değeri

Herhangi bir öğede kontrol başarısız olursa false, tümü geçerse true.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [ICollection](../../../system.collections.generic/icollection/)
* Yapı [CollectionAssertHelper](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)