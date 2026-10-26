---
title: AsCast()
second_title: Aspose.Slides for C++ API Referansı
description: Kaynak türü, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürür. Basit yapılandırıcı benzeri döküm gerektiğinde kullanılır.
type: docs
weight: 2640
url: /tr/system/ascast/
---
## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Basit yapılandırıcı benzeri dönüşüm gerektiğinde kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Kaynak ve sonuç türleri aynı olduğunda kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. İstisna sargıları için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Nesneyi istisna olarak dökmek için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Kaynak ve sonuç her ikisi de akıllı işaretçiler olduğunda kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu. Dönüştürme mevcut değilse nullptr döner.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Kaynak ve sonuç her ikisi de akıllı işaretçiler olduğunda (sonuç türünde açık SmartPtr<...> ile) kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu. Dönüştürme mevcut değilse nullptr döner.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Nesneyi nullable'a kutudan çıkarmak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu. Dönüştürme mevcut değilse boş nullable döner.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Nesne olmayan türe geçersiz kutudan çıkarma.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Her zaman null döner.

## System::AsCast(const Source\&) fonksiyon


Nesne olmayan türe geçersiz kutudan çıkarma.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Her zaman null döner.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Nullable nesneyi kutulamak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Yaygın nesneyi kutulamak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Yaygın nesneyi kutulamak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Dizeyi kutudan çıkarmak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. nullptr durumunda kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu.

## System::AsCast(const Source\&) fonksiyon


Kaynak tür, 'as' operatör dökümü kullanılarak sonuç türüne dönüştürülür. Diziler arasında dönüştürme için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Source | Kaynak tür. |
| Result | Sonuç tür. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) dönüşüm için. |

### Dönüş Değeri

Dönüşüm sonucu. Dönüştürme mevcut değilse herhangi bir dizi üyesi için nullptr döner.

## See Also

* Typedef [Exception](../exception/)
* Yapı [CastResult](../castresult/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)