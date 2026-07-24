---
title: MakeObject()
second_title: Aspose.Slides for C++ API Referansı
description: Yığın üzerinde bir nesne oluşturur ve ona paylaşımlı işaretçi döndürür.
type: docs
weight: 2887
url: /tr/system/makeobject/
---
## System::MakeObject(Args\&&...) fonksiyon

Yığın üzerinde bir nesne oluşturur ve ona paylaşımlı işaretçi döndürür.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Örneklemek için sınıf. |
| Args | Yapıcı argümanlarının türleri. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | Args\&&... | Yapıcı argümanları. |

### Dönüş Değeri

[SmartPtr](../smartptr/) yeni oluşturulan nesneye, her zaman paylaşılan modda.

## System::MakeObject(Args\&&...) fonksiyon

Yığın üzerinde bir nesne oluşturur ve ona paylaşımlı işaretçi döndürür.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [SmartPtr](../smartptr/) sınıfı örneklemek için. |
| Args | Yapıcı argümanlarının türleri. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | Args\&&... | Yapıcı argümanları. |

### Dönüş Değeri

[SmartPtr](../smartptr/) yeni oluşturulan nesneye, her zaman paylaşılan modda.

## İlgili

* Sınıf [SmartPtr](../smartptr/)
* Yapı [IsSmartPtr](../issmartptr/)
* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)