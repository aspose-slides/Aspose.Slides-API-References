---
title: DynamicCast()
second_title: Aspose.Slides için C++ API Referansı
description: Exception nesnelerinde dinamik dönüşüm gerçekleştirir.
type: docs
weight: 2536
url: /tr/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) fonksiyon


Exception nesnelerinde dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef Exception tipi. |
| TFrom | Kaynak Exception tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const TFrom\& | Kaynak işaretçi. |

### Dönüş Değeri

Dönüşüm izni varsa dönüşüm sonucu.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) fonksiyon


[SmartPtr](../smartptr/) nesnelerinde dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tür. |
| TFrom | Kaynak işaret edilen tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Kaynak işaretçi. |

### Dönüş Değeri

Dönüşüm izni varsa dönüşüm sonucu.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(SmartPtr\<TFrom\>) fonksiyon


Dönüşüm aracılığıyla kutulanmış enum değerini kutudan çıkarır.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef enum tipi. |
| TFrom | Kaynak işaret edilen tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Verinin kutusundan çıkarılacağı nesneye işaretçi. |

### Dönüş Değeri

Kutudan çıkarılmış enum değeri.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(std::nullptr_t) fonksiyon


null nesnelerinde dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tür. |

### Dönüş Değeri

nullptr.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(TFrom\&) fonksiyon


İşaretçi olmayan nesnelerde dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef tür. |
| TFrom | Kaynak tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | TFrom\& | Kaynak nesne. |

### Dönüş Değeri

Dönüşüm sonucu.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(SmartPtr\<TFrom\>) fonksiyon


Objects nesnelerinde Exception nesnelerine dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef Exception tipi. |
| TFrom | [Object](../object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Kaynak işaretçi. |

### Dönüş Değeri

Dönüşüm izni varsa dönüşüm sonucu.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(TFrom) fonksiyon


IntPtr'den işaretçiye dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef tür. |
| TFrom | Kaynak tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | TFrom | Kaynak IntPtr değeri. |

### Dönüş Değeri

Dönüşüm sonucu.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## İlgili

* Sınıf [SmartPtr](../smartptr/)
* Sınıf [Object](../object/)
* Yapı [IsExceptionWrapper](../isexceptionwrapper/)
* Yapı [CastResult](../castresult/)
* Yapı [IsSmartPtr](../issmartptr/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)