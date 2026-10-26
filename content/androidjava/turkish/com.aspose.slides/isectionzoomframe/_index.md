---
title: ISectionZoomFrame
second_title: Java API Referansı ile Android için Aspose.Slides
description: Bir slayttaki Section Zoom nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/isectionzoomframe/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Bir slayttaki Section Zoom nesnesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Section Zoom nesnesinin bağlı olduğu bölüm nesnesini alır veya ayarlar. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Section Zoom nesnesinin bağlı olduğu bölüm nesnesini alır veya ayarlar. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


Section Zoom nesnesinin bağlı olduğu bölüm nesnesini alır veya ayarlar. Okuma/Yazma [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


Section Zoom nesnesinin bağlı olduğu bölüm nesnesini alır veya ayarlar. Okuma/Yazma [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |