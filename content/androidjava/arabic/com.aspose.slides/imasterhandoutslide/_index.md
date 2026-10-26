---
title: IMasterHandoutSlide
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل الشريحة الرئيسية للنشرات.
type: docs
url: /ar/com.aspose.slides/imasterhandoutslide/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

يمثل الشريحة الرئيسية للنشرات.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يعيد مدير HeaderFooter لشريحة التسليم الرئيسية. |
| [getDrawingGuides()](#getDrawingGuides--) | يعيد مجموعة من دلائل الرسم لشريحة التسليم الرئيسية. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

يعيد مدير HeaderFooter لشريحة التسليم الرئيسية. للقراءة فقط [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**إرجاع:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

يعيد مجموعة من دلائل الرسم لشريحة التسليم الرئيسية. للقراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
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


**إرجاع:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)