---
title: MasterHandoutSlide
second_title: مرجع API ل Aspose.Slides للـ Java
description: يمثل الشريحة الرئيسية للنشرات.
type: docs
url: /ar/com.aspose.slides/masterhandoutslide/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

يمثل الشريحة الرئيسية للنشرة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يعيد HeaderFooter manager للشريحة الرئيسية للنشرة. |
| [getThemeManager()](#getThemeManager--) | يعيد theme manager. |
| [getDrawingGuides()](#getDrawingGuides--) | يعيد مجموعة من drawing guides للشريحة الرئيسية للنشرة. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها، تُعيد هذه الخاصية دائمًا false. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها، تُعيد هذه الخاصية دائمًا false. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

يعيد HeaderFooter manager للشريحة الرئيسية للنشرة. قراءة فقط [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**الإرجاع:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

يعيد theme manager. قراءة فقط [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**الإرجاع:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

يعيد مجموعة من drawing guides للشريحة الرئيسية للنشرة. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // إضافة دليل الرسم الأفقي الجديد فوق مركز الشريحة
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)