---
title: CanCast()
second_title: Aspose.Slides for C++ API Referansı
description: Casting olasılığını kontrol eder.
type: docs
weight: 40
url: /tr/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) fonksiyon


Casting olasılığını kontrol eder.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Dönüş Değeri

Casting sonrası nullptr olmayan bir değer döndürülürse true, aksi takdirde false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonksiyon


Casting olasılığını kontrol eder.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Dönüş Değeri

Casting sonrası nullptr olmayan bir değer döndürülürse true, aksi takdirde false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonksiyon


Casting olasılığını kontrol eder.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Dönüş Değeri

Casting sonrası nullptr olmayan bir değer döndürülürse true, aksi takdirde false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonksiyon


Casting olasılığını kontrol eder.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Dönüş Değeri

Her zaman true döner.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonksiyon


Casting olasılığını kontrol eder.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Dönüş Değeri

Casting sonrası nullptr olmayan bir değer döndürülürse true, aksi takdirde false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonksiyon


Casting olasılığını kontrol eder.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Dönüş Değeri

Her zaman true döner.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonksiyon


Casting olasılığını kontrol eder.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Dönüş Değeri

Cast işlemi başarılı bir şekilde gerçekleştirilmişse true, aksi takdirde false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonksiyon


Casting olasılığını kontrol eder.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Dönüş Değeri

Her zaman false döner.

## İlgili

* Yapı [CastType](../casttype/)
* Ad Alanı [System::Collections::Generic::Details::CastRules](../)
* Kütüphane [Aspose.Slides](../../)