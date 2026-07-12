---
title: IColorChange
second_title: Aspose.Slides for Android için Java API Referansı
description: Renk Değişim etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/icolorchange/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Bir Renk Değişim etkisini temsil eder. FromColor örnekleri ToColor örnekleriyle değiştirilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFromColor()](#getFromColor--) | Değiştirilecek renk. |
| [getToColor()](#getToColor--) | Değiştirecek renk. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Değiştirilecek renk. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Değiştirecek renk. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)