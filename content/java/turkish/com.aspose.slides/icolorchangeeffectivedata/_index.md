---
title: IColorChangeEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Renk Değişikliği etkisini temsil eden değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/icolorchangeeffectivedata/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Değiştirilen renk etkisini temsil eden değiştirilemez bir nesne. FromColor örnekleri ToColor örnekleriyle değiştirilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFromColor()](#getFromColor--) | Değiştirilecek renk. |
| [getToColor()](#getToColor--) | Yerine konulacak renk. |
| [getUseAlpha()](#getUseAlpha--) | Alfa bileşeninin kullanılmasını belirleyen bir boolean değeri döndürür. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```

Değiştirilecek renk. Salt okunur java.awt.Color.

**Döndürür:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```

Yerine konulacak renk. Salt okunur java.awt.Color.

**Döndürür:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```

Alfa bileşeninin kullanılmasını belirleyen bir boolean değeri döndürür. Salt okunur boolean.

**Döndürür:**
boolean