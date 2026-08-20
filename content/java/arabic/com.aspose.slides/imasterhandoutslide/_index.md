---
title: IMasterHandoutSlide
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل الشريحة الرئيسية للنُسخ.
type: docs
url: /ar/com.aspose.slides/imasterhandoutslide/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

يمثل الشريحة الرئيسية للنُسخ.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرجع HeaderFooter manager للشريحة الرئيسية للنُسخ. |
| [getDrawingGuides()](#getDrawingGuides--) | يرجع مجموعة من أدلة الرسم للشريحة الرئيسية للنُسخ. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


يرجع HeaderFooter manager للشريحة الرئيسية للنُسخ. للقراءة فقط [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**الإرجاع:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


يرجع مجموعة من أدلة الرسم للشريحة الرئيسية للنُسخ. للقراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // إضافة دليل الرسم الأفقي الجديد فوق مركز الشريحة
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)