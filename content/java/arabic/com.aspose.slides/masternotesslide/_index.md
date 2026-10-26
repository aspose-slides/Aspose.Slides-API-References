---
title: MasterNotesSlide
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل الشريحة الرئيسة للملاحظات.
type: docs
url: /ar/com.aspose.slides/masternotesslide/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

يمثل الشريحة الرئيسية للملاحظات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | تحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | تحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يعيد مدير HeaderFooter لشريحة الملاحظات الرئيسية. |
| [getThemeManager()](#getThemeManager--) | يعيد مدير السمة. |
| [getNotesStyle()](#getNotesStyle--) | يعيد نمط نص ملاحظة. |
| [getDrawingGuides()](#getDrawingGuides--) | يعيد مجموعة من أدلة الرسم لشريحة الملاحظات الرئيسية. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

تحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها، ترجع هذه الخاصية دائمًا false. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

تحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها، ترجع هذه الخاصية دائمًا false. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

يعيد مدير HeaderFooter لشريحة الملاحظات الرئيسية. قراءة فقط [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**القيمة المرجعة:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

يعيد مدير السمة. قراءة فقط [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**القيمة المرجعة:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

يعيد نمط نص ملاحظة. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**القيمة المرجعة:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

يعيد مجموعة من أدلة الرسم لشريحة الملاحظات الرئيسية. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // إضافة دليل الرسم الأفقي الجديد أسفل مركز الشريحة
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)