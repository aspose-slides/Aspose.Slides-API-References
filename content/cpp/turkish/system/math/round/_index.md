---
title: Round()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değeri en yakın tam sayıya yuvarlar.
type: docs
weight: 157
url: /tr/system/math/round/
---
## Math::Round(double) metodu


Belirtilen değeri en yakın tam sayıya yuvarlar.

```cpp
static double System::Math::Round(double a)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | **double** | Yuvarlanacak değer |

### Dönüş Değeri

**a** en yakın tam sayıya yuvarlandı

## Math::Round(double, int) metodu


Belirtilen değeri, belirtilen sayıda kesirli basamağa sahip en yakın değere yuvarlar.

```cpp
static double System::Math::Round(double value, int digits)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **double** | Yuvarlanacak değer |
| digits | int | Yuvarlanmış değerdeki kesirli basamak sayısı |

### Dönüş Değeri

Belirtilen basamak sayısına sahip, **value**'a en yakın sayı

## Math::Round(double, MidpointRounding) metodu


Belirtilen değeri en yakın tam sayıya yuvarlar. Bir parametre, belirtilen değer iki en yakın sayıya eşit uzaklıkta olduğunda işlevin davranışını belirtir.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **double** | Yuvarlanacak değer |
| mode | [MidpointRounding](../../midpointrounding/) | Belirtilen değer iki en yakın sayıya eşit uzaklıkta olduğunda yuvarlama nasıl yapılacağını belirtir. |

### Dönüş Değeri

**value** en yakın tam sayıya yuvarlandı

## Math::Round(double, int, MidpointRounding) metodu


Belirtilen değeri, belirtilen sayıda kesirli basamağa sahip en yakın değere yuvarlar. Bir parametre, belirtilen değer iki en yakın sayıya eşit uzaklıkta olduğunda işlevin davranışını belirtir.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **double** | Yuvarlanacak değer |
| digits | int | Yuvarlanmış değerdeki kesirli basamak sayısı |
| mode | [MidpointRounding](../../midpointrounding/) | Belirtilen değer iki en yakın sayıya eşit uzaklıkta olduğunda yuvarlama nasıl yapılacağını belirtir. |

### Dönüş Değeri

Belirtilen basamak sayısına sahip, **value**'a en yakın sayı

## Math::Round(const Decimal\&) metodu


Belirtilen değeri en yakın tam sayıya yuvarlar.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Yuvarlanacak değer |

### Dönüş Değeri

**d** en yakın tam sayıya yuvarlandı

## Math::Round(const Decimal\&, int) metodu


Belirtilen değeri, belirtilen sayıda kesirli basamağa sahip en yakın değere yuvarlar.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Yuvarlanacak değer |
| digits | int | Yuvarlanmış değerdeki kesirli basamak sayısı |

### Dönüş Değeri

Belirtilen basamak sayısına sahip, **value**'a en yakın sayı

## Math::Round(const Decimal\&, MidpointRounding) metodu


Belirtilen değeri en yakın tam sayıya yuvarlar. Bir parametre, belirtilen değer iki en yakın sayıya eşit uzaklıkta olduğunda işlevin davranışını belirtir.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Yuvarlanacak değer |
| mode | [MidpointRounding](../../midpointrounding/) | Belirtilen değer iki en yakın sayıya eşit uzaklıkta olduğunda yuvarlama nasıl yapılacağını belirtir. |

### Dönüş Değeri

**d** en yakın tam sayıya yuvarlandı

## Math::Round(const Decimal\&, int, MidpointRounding) metodu


Belirtilen değeri, belirtilen sayıda kesirli basamağa sahip en yakın değere yuvarlar. Bir parametre, belirtilen değer iki en yakın sayıya eşit uzaklıkta olduğunda işlevin davranışını belirtir.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Yuvarlanacak değer |
| digits | int | Yuvarlanmış değerdeki kesirli basamak sayısı |
| mode | [MidpointRounding](../../midpointrounding/) | Belirtilen değer iki en yakın sayıya eşit uzaklıkta olduğunda yuvarlama nasıl yapılacağını belirtir. |

### Dönüş Değeri

Belirtilen basamak sayısına sahip, **value**'a en yakın sayı

## Ayrıca Bakınız

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)