---
title: DynamicCast_noexcept()
second_title: Aspose.Slides for C++ API Referansı
description: Eski kullanımdan kaldırılmış dönüşümler. Gelecek sürümlerde kaldırılacak.
type: docs
weight: 2523
url: /tr/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) fonksiyon


Eski kullanımdan kalkmış dönüşümler. Gelecek sürümlerde kaldırılacaktır.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef Exception türü. |
| TFrom | Kaynak Exception türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const TFrom\& | Kaynak işaretçi. |

### Dönüş Değeri

Cast sonucu eğer cast izinliyse; aksi takdirde nullptr.

## Açıklamalar


Exception nesneleri üzerinde dinamik cast gerçekleştirir. Artık kullanılmıyor
:   Geriye uyumluluk için bırakıldı. Bunun yerine AsCast kullanın.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) fonksiyon


[SmartPtr](../smartptr/) nesneleri üzerinde dinamik cast gerçekleştirir. Artık kullanılmıyor

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaretçi türü. |
| TFrom | Kaynak işaretçi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Kaynak işaretçi. |

### Dönüş Değeri

Cast sonucu eğer cast izinliyse; aksi takdirde nullptr.

Artık kullanılmıyor
:   Geriye uyumluluk için bırakıldı. Bunun yerine AsCast kullanın.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) fonksiyon


Objects nesneleri üzerinde Exception nesnelerine dinamik cast gerçekleştirir. Artık kullanılmıyor

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef Exception türü. |
| TFrom | [Object](../object/) türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Kaynak işaretçi. |

### Dönüş Değeri

Cast sonucu eğer cast izinliyse; aksi takdirde nullptr.

Artık kullanılmıyor
:   Geriye uyumluluk için bırakıldı. Bunun yerine AsCast kullanın.

## İlgili

* Sınıf [SmartPtr](../smartptr/)
* Sınıf [Object](../object/)
* Yapı [IsExceptionWrapper](../isexceptionwrapper/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)