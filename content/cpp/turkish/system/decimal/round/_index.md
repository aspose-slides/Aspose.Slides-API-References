---
title: Round()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değeri en yakın tamsayıya yuvarlar. Belirtilen değer iki en yakın sayıya eşit mesafede olduğunda fonksiyonun davranışını belirten bir parametre.
type: docs
weight: 404
url: /tr/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) metodu

Belirtilen değeri en yakın tamsayıya yuvarlar. Bir parametre, belirtilen değer iki en yakın sayıya eşit mesafede olduğunda fonksiyonun davranışını belirtir.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| d | const [Decimal](../)\& | Yuvarlanacak değer |
| mode | [MidpointRounding](../../midpointrounding/) | **value** iki en yakın sayıya eşit mesafede olduğunda yuvarlamanın nasıl yapılacağını belirtir. |

### Dönüş Değeri

**d** en yakın tamsayı değerine yuvarlanmış

## Decimal::Round(const Decimal\&, int, MidpointRounding) metodu

Belirtilen değeri, belirtilen sayıda kesirli basamağa sahip en yakın değere yuvarlar. Bir parametre, belirtilen değer iki en yakın sayıya eşit mesafede olduğunda fonksiyonun davranışını belirtir.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| d | const [Decimal](../)\& | Yuvarlanacak değer |
| digits | int | Yuvarlanmış değerdeki kesirli basamak sayısı |
| mode | [MidpointRounding](../../midpointrounding/) | **value** iki en yakın sayıya eşit mesafede olduğunda yuvarlamanın nasıl yapılacağını belirtir. |

### Dönüş Değeri

Belirtilen basamak sayısına sahip, **value** değerine en yakın sayı

## Ayrıca Bakınız

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)