---
title: Cast()
second_title: Aspose.Slides için C++ API Referansı
description: Kaynak türü, sonuç türüne dönüştürülür. Kaynak ve sonuç türleri aynı olduğunda kullanılır.
type: docs
weight: 14
url: /tr/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) fonksiyon


Kaynak türü sonuç türüne dönüştürülür. Kaynak ve sonuç türleri aynı olduğunda kullanılır.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Dönüş Değeri

Dönüştürme sonucu.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonksiyon


Kaynak türü sonuç türüne dönüştürülür. Kaynak türü, sonuç türüne statik olarak dönüştürülürse kullanılır.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Dönüş Değeri

Dönüştürme sonucu.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonksiyon


Kaynak türü sonuç türüne dönüştürülür. Türler aynı olmadığında ve kaynak türü statik olarak sonuç türüne dönüştürülemediğinde kullanılır.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Dönüş Değeri

Dönüştürme sonucu.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonksiyon


Kaynak türü sonuç türüne dönüştürülür. Kaynak türü, [Nullable](../../system/nullable/) sınıfı örneğine kutulanıyorken kullanılır.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Dönüş Değeri

Dönüştürme sonucu.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonksiyon


Kaynak türü sonuç türüne dönüştürülür. Kaynak türü, [Nullable](../../system/nullable/) sınıfı örneğinden kutusundan çıkarılırken kullanılır.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Dönüş Değeri

Dönüştürme sonucu.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonksiyon


Kaynak türü sonuç türüne dönüştürülür. Kaynak türü, [Object](../../system/object/) sınıfı örneğine kutulanıyorken kullanılır.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Dönüş Değeri

Dönüştürme sonucu.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonksiyon


Kaynak türü sonuç türüne dönüştürülür. Kaynak türü, [Object](../../system/object/) sınıfı örneğinden kutusundan çıkarılırken kullanılır.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Dönüş Değeri

Dönüştürme sonucu.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonksiyon


Kaynak türü sonuç türüne dönüştürülür. Dönüştürme geçersiz olduğunda veya dönüşüm açık olduğunda kullanılır.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Dönüş Değeri

Dönüştürme sonucu.

## İlgili

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)