---
title: Equals< float, float >()
second_title: C++ için Aspose.Slides API Referansı
description: "Tek duyarlıklı kayan nokta değerleri için özelleştirme. IEC 60559:1989 tarafından tanımlanan iki kayan nokta NaN'ının her zaman eşit olmayan olarak karşılaştırılması gerekirken, System.Object.Equals sözleşmesi, geçersiz kılmaların bir eşdeğerlik operatörü gereksinimlerini karşılamasını zorunlu kılar. Bu nedenle, System.Double.Equals ve System.Single.Equals iki NaN karşılaştırıldığında True döndürür, eşitlik operatörü ise bu durumda standartta gerektiği gibi False döndürür."
type: docs
weight: 2705
url: /tr/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) fonksiyon

Tek duyarlıklı kayan nokta değerleri için özelleştirme. IEC 60559:1989 tarafından tanımlanan iki kayan nokta NaN'ının her zaman eşit olmayan olarak karşılaştırılması gerekirken, [System.Object.Equals](../object/equals/) sözleşmesi, geçersiz kılmaların bir eşdeğerlik operatörü gereksinimlerini karşılamasını zorunlu kılar. Bu nedenle, System.Double.Equals ve System.Single.Equals iki NaN karşılaştırıldığında True döndürür, eşitlik operatörü ise bu durumda standartta gerektiği gibi False döndürür.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const **float**\& | İlk karşılaştırılan |
| b | const **float**\& | İkinci karşılaştırılan |

### Dönüş Değeri

Her iki değer NaN ise veya eşitse True, aksi takdirde - false

## Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)