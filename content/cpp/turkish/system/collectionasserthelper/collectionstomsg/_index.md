---
title: CollectionsToMsg()
second_title: Aspose.Slides for C++ API Referansı
description: Mesaj temsili için iki koleksiyonu serileştirir.
type: docs
weight: 53
url: /tr/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) yöntemi


İki koleksiyonu mesaj temsili için serileştirir.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Beklenen koleksiyon öğesi tipi. |
| T2 | Gerçek koleksiyon öğesi tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | Sonuç mesajında beklenen değerin önüne eklenen özel bir dize. |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Beklenen koleksiyon. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Gerçek koleksiyon. |

### Dönüş değeri

Koleksiyonların içeriği hakkında kullanıcı dostu bir mesaj.

## Daha fazla bilgi

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [IEnumerable](../../../system.collections.generic/ienumerable/)
* Yapı [CollectionAssertHelper](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)