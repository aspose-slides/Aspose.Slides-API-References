---
title: IBlurEffectiveData
second_title: Aspose.Slides for Android için Java API Referansı
description: Dolgu dahil olmak üzere tüm şekle uygulanan bir Blur efekti temsil eden değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/iblureffectivedata/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Değiştirilemez nesne, dolgu dahil olmak üzere tüm şekle uygulanan bir Blur efekti temsil eder. Alfa dahil olmak üzere tüm renk kanalları etkilenir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Bulanıklık yarıçapını döndürür veya ayarlar. |
| [getGrow()](#getGrow--) | Nesnenin sınırlamalarının bulanıklaştırma sonucunda büyütülüp büyütülmeyeceğini belirler. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Bulanıklık yarıçapını döndürür veya ayarlar. Salt okunur double.

**Döndürür:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Sınırlamaların bulanıklaştırma sonucunda büyütülüp büyütülmeyeceğini belirler. True, sınırlamaların büyütüldüğünü, false ise büyütülmediğini gösterir. Salt okunur boolean.

**Döndürür:**
boolean