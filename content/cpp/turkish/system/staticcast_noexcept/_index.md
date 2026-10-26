---
title: StaticCast_noexcept()
second_title: Aspose.Slides for C++ API Referansı
description: SmartPtr nesneleri üzerinde statik dönüşüm gerçekleştirir.
type: docs
weight: 2549
url: /tr/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) fonksiyon

[SmartPtr](../smartptr/) nesneleri üzerinde statik cast gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Kaynak gösterici. |

### Dönüş Değeri

Cast sonucu, cast izin veriliyorsa döndürülür; aksi takdirde nullptr.

Kullanım Dışı
:   Geriye dönük uyumluluk için bırakılmıştır. Bunun yerine AsCast kullanın.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) fonksiyon

[WeakPtr](../weakptr/) nesneleri üzerinde statik cast gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Kaynak gösterici. |

### Dönüş Değeri

Cast sonucu, cast izin veriliyorsa döndürülür; aksi takdirde nullptr.

Kullanım Dışı
:   Geriye dönük uyumluluk için bırakılmıştır. Bunun yerine AsCast kullanın.

## System::StaticCast_noexcept(const TFrom\&) fonksiyon

Exception nesneleri üzerinde statik cast gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef Exception tipi. |
| TFrom | Kaynak Exception tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const TFrom\& | Kaynak gösterici. |

### Dönüş Değeri

Cast sonucu, cast izin veriliyorsa döndürülür; aksi takdirde nullptr.

Kullanım Dışı
:   Geriye dönük uyumluluk için bırakılmıştır. Bunun yerine AsCast kullanın.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) fonksiyon

Nesneleri Exception nesnelerine statik cast gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef Exception tipi. |
| TFrom | [Object](../object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Kaynak gösterici. |

### Dönüş Değeri

Cast sonucu, cast izin veriliyorsa döndürülür; aksi takdirde nullptr.

Kullanım Dışı
:   Geriye dönük uyumluluk için bırakılmıştır. Bunun yerine AsCast kullanın.

## Ayrıca Bakınız

* Sınıf [SmartPtr](../smartptr/)
* Sınıf [WeakPtr](../weakptr/)
* Sınıf [Object](../object/)
* Yapı [IsExceptionWrapper](../isexceptionwrapper/)
* Yapı [CastResult](../castresult/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)