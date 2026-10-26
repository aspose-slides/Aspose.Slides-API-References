---
title: IBlurEffectiveData
second_title: Aspose.Slides için Java API Referansı
description: Dolgu dahil tüm şekle uygulanan bir Blur etkisini temsil eden değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/iblureffectivedata/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Tüm şekle, doldurması dahil, uygulanmış bir Blur etkisini temsil eden değiştirilemez nesne. Alfa dahil tüm renk kanalları etkilenir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Bulanık yarıçapını alır veya ayarlar. |
| [getGrow()](#getGrow--) | Nesnenin sınırlarının bulanıklaştırma sonucunda büyütülüp büyütülmeyeceğini belirler. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Bulanık yarıçapını alır veya ayarlar. Salt okunur double.

**Döndürür:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Nesnenin sınırlarının bulanıklaştırma sonucunda büyütülüp büyütülmeyeceğini belirler. True, sınırların büyütüldüğünü; false, büyütülmediğini gösterir. Salt okunur boolean.

**Döndürür:**
boolean