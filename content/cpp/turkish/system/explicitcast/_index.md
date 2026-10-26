---
title: ExplicitCast()
second_title: Aspose.Slides for C++ API Referansı
description: Açık dönüşüm kullanarak kaynak türü, sonuç türüne dönüştürür. Kaynak ve sonuç türleri aynı olduğunda kullanılır.
type: docs
weight: 2627
url: /tr/system/explicitcast/
---
## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Kaynak ve sonuç türleri aynı olduğunda kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Basit yapılandırıcı benzeri dönüşüm gerektiğinde kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. İstisna sarmalayıcıları için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Nesneyi istisna olarak dönüştürmek için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Kaynak ve sonuç ikisi de akıllı işaretçiler olduğunda (sonuç türünde açık SmartPtr<...> olmadan) kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(Source) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Ham işaretçiyi akıllı işaretçiye dönüştürürken kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | Source | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Kaynak ve sonuç ikisi de akıllı işaretçiler olduğunda (sonuç türünde açık SmartPtr<...> ile) kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Nesneyi nullable hâle getirmek için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Nullable'ı kutulamaya (boxing) almak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Nullable nesneyi kutudan çıkarmak (unboxing) için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Enum kutulamaya (boxing) için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Değer türlerini, akıllı işaretçi olarak referans edilmesi gerektiğinde heap'e kopyalamak için kullanılır (arayüz türüyle kısıtlanmış jeneriklerde, bu arayüzü uygulayan yapı ile özelleştirildiğinde).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Değer türlerinden arayüzleri elde etmek için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Ortak kutulamaya (boxing) için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. [System::String](../string/) kutulamaya (boxing) için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Arayüzleri kutudan çıkarmak (unboxing) için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Ortak kutudan çıkarma (unboxing) için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. nullptr dönüşümü için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## System::ExplicitCast(const Source\&) fonksiyon


Kaynak türü, sonuç türüne açık dönüşüm kullanılarak dönüştürür. Diziler arasında dönüşüm için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüştürmek için. |

### Dönüş değeri

Dönüşüm sonucu.

## Ayrıca bakınız

* Typedef [Exception](../exception/)
* Sınıf [SmartPtr](../smartptr/)
* Sınıf [BoxedValueBase](../boxedvaluebase/)
* Yapı [CastResult](../castresult/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)