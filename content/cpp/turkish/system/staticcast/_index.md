---
title: StaticCast()
second_title: Aspose.Slides for C++ API Referansı
description: SmartPtr nesneleri üzerinde statik dönüşüm gerçekleştirir.
type: docs
weight: 2562
url: /tr/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) fonksiyon


[SmartPtr](../smartptr/) nesneleri üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef gösterilen tip. |
| TFrom | Kaynak gösterilen tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Kaynak işaretçi. |

### Dönüş Değeri

Cast sonucu, cast izinliyse döndürülür.

Kullanımdan kaldırılmış
:   Geriye uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## System::StaticCast(WeakPtr\<TFrom\> const\&) fonksiyon


[WeakPtr](../weakptr/) nesneleri üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef gösterilen tip. |
| TFrom | Kaynak gösterilen tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Kaynak işaretçi. |

### Dönüş Değeri

Cast sonucu, cast izinliyse döndürülür.

Kullanımdan kaldırılmış
:   Geriye uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## System::StaticCast(std::nullptr_t) fonksiyon


Null nesneler üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef gösterilen tip. |

### Dönüş Değeri

nullptr.

Kullanımdan kaldırılmış
:   Geriye uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## System::StaticCast(TFrom) fonksiyon


Aritmetik tipler için uzmanlaşma.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) fonksiyon


[String](../string/)'den [String](../string/)'e dönüşüm işlenir.

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) fonksiyon


Aritmetik tipler için uzmanlaşma.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) fonksiyon


İşaretçi olmayan nesneler üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef tip. |
| TFrom | Kaynak tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const TFrom\& | Kaynak nesne. |

### Dönüş Değeri

Cast sonucu, cast izinliyse döndürülür.

Kullanımdan kaldırılmış
:   Geriye uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## System::StaticCast(const TFrom\&) fonksiyon


İstisna nesneleri üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef İstisna tipi. |
| TFrom | Kaynak İstisna tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const TFrom\& | Kaynak işaretçi. |

### Dönüş Değeri

Cast sonucu, cast izinliyse döndürülür.

Kullanımdan kaldırılmış
:   Geriye uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## System::StaticCast(SmartPtr\<TFrom\>) fonksiyon


Nesnelerden İstisna nesnelerine statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef İstisna tipi. |
| TFrom | [Object](../object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Kaynak işaretçi. |

### Dönüş Değeri

Cast sonucu, cast izinliyse döndürülür.

Kullanımdan kaldırılmış
:   Geriye uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Sınıf [SmartPtr](../smartptr/)
* Sınıf [WeakPtr](../weakptr/)
* Sınıf [String](../string/)
* Sınıf [Object](../object/)
* Yapı [IsExceptionWrapper](../isexceptionwrapper/)
* Yapı [CastResult](../castresult/)
* Yapı [IsSmartPtr](../issmartptr/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)