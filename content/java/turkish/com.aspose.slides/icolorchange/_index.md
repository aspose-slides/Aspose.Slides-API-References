---
title: IColorChange
second_title: Aspose.Slides for Java API Referansı
description: Bir Renk Değişikliği etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/icolorchange/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Bir Renk Değişikliği etkisini temsil eder. FromColor örnekleri ToColor örnekleriyle değiştirilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFromColor()](#getFromColor--) | Değiştirilecek renk. |
| [getToColor()](#getToColor--) | Değiştirecek renk. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Değiştirilecek renk. Yalnızca okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Değiştirecek renk. Yalnızca okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)