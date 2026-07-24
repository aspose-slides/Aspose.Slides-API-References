---
title: Round()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen değeri en yakın tam sayıya yuvarlar.
type: docs
weight: 157
url: /tr/system/mathf/round/
---
## MathF::Round(float) metodu

Belirtilen değeri en yakın tam sayıya yuvarlar.

```cpp
static float System::MathF::Round(float a)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | **float** | Yuvarlanacak değer |

### Dönüş Değeri

**a** en yakın tam sayıya yuvarlanmış

## MathF::Round(float, int) metodu

Belirtilen değeri, belirtilen basamak sayısına sahip en yakın değere yuvarlar.

```cpp
static float System::MathF::Round(float value, int digits)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **float** | Yuvarlanacak değer |
| digits | int | Yuvarlanmış değerdeki ondalık basamak sayısı |

### Dönüş Değeri

Belirtilen basamak sayısına sahip, **value** en yakın sayı

## MathF::Round(float, MidpointRounding) metodu

Belirtilen değeri en yakın tam sayıya yuvarlar. Bir parametre, belirtilen değer iki en yakın sayıya eşit mesafedeyse fonksiyonun davranışını belirtir.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **float** | Yuvarlanacak değer |
| mode | [MidpointRounding](../../midpointrounding/) | **value** iki en yakın sayıya eşit mesafedeyse yuvarlamanın nasıl yapılacağını belirtir. |

### Dönüş Değeri

**value** en yakın tam sayıya yuvarlanmış

## MathF::Round(float, int, MidpointRounding) metodu

Belirtilen değeri, belirtilen basamak sayısına sahip en yakın değere yuvarlar. Bir parametre, belirtilen değer iki en yakın sayıya eşit mesafedeyse fonksiyonun davranışını belirtir.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **float** | Yuvarlanacak değer |
| digits | int | Yuvarlanmış değerdeki ondalık basamak sayısı |
| mode | [MidpointRounding](../../midpointrounding/) | **value** iki en yakın sayıya eşit mesafedeyse yuvarlamanın nasıl yapılacağını belirtir. |

### Dönüş Değeri

Belirtilen basamak sayısına sahip, **value** en yakın sayı

## Diğer

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Kütüphane [Aspose.Slides](../../../)