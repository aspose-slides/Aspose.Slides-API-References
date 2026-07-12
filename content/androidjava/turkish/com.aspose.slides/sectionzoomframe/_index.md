---
title: SectionZoomFrame
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Bir slaytta Section Zoom nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/sectionzoomframe/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Bir slaytta Section Zoom nesnesini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Section Zoom nesnesinin bağlandığı bölüm nesnesini alır veya ayarlar. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Section Zoom nesnesinin bağlandığı bölüm nesnesini alır veya ayarlar. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


Section Zoom nesnesinin bağlandığı bölüm nesnesini alır veya ayarlar. Okunur/Yazılabilir [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


Section Zoom nesnesinin bağlandığı bölüm nesnesini alır veya ayarlar. Okunur/Yazılabilir [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |