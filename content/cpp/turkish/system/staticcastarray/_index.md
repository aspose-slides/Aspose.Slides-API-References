---
title: StaticCastArray()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizinin öğelerini farklı bir tipe dönüştürür. From SmartPtr nesnesi olduğunda geçersiz kılar.
type: docs
weight: 2978
url: /tr/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) fonksiyon

Belirtilen dizinin öğelerini farklı bir tipe dönüştürür. From [SmartPtr](../smartptr/) nesnesi olduğunda geçersiz kılar.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| To | Belirtilen dizinin öğelerinin dönüştürüleceği tip |
| From | Dönüştürülecek öğelerin tipi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Dönüştürülecek öğeleri içeren diziye işaretçi |

### Dönüş Değeri

**from** öğelerine eşdeğer **To** tipinde yeni bir diziye işaretçi

Kullanım dışı
:   Geriye dönük uyumluluk sağlamak için eklendi. Bunun yerine ExplicitCast kullanın.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) fonksiyon

Belirtilen dizinin öğelerini farklı bir tipe dönüştürür. From Boxable ve To [Object](../object/)[] olduğunda geçersiz kılar.

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| To | Belirtilen dizinin öğelerinin dönüştürüleceği tip |
| From | Dönüştürülecek öğelerin tipi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Dönüştürülecek öğeleri içeren diziye işaretçi |

### Dönüş Değeri

**from** öğelerine eşdeğer **To** tipinde yeni bir diziye işaretçi

Kullanım dışı
:   Geriye dönük uyumluluk sağlamak için eklendi. Bunun yerine ExplicitCast kullanın.

## İlgili

* Tip Tanımı [SharedPtr](../sharedptr/)
* Sınıf [Array](../array/)
* Sınıf [Object](../object/)
* Yapı [IsSmartPtr](../issmartptr/)
* Yapı [IsBoxable](../isboxable/)
* AdAlanı [System](../)
* Kütüphane [Aspose.Slides](../../)