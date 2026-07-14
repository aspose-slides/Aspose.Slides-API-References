---
title: MasterNotesSlide
second_title: Aspose.Slides for Android عبر مرجع Java API
description: يمثل الشريحة الرئيسية للملاحظات.
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
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يعيد مدير HeaderFooter لشريحة الملاحظات الرئيسية. |
| [getThemeManager()](#getThemeManager--) | يعيد مدير السمة. |
| [getNotesStyle()](#getNotesStyle--) | يعيد نمط نص الملاحظات. |
| [getDrawingGuides()](#getDrawingGuides--) | يعيد مجموعة من أدلة الرسم لشريحة الملاحظات الرئيسية. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها هذه الخاصية دائمًا تُعيد false. قابل للقراءة/الكتابة boolean.

**الإرجاع:**  
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها هذه الخاصية دائمًا تُعيد false. قابل للقراءة/الكتابة boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

يعيد مدير HeaderFooter لشريحة الملاحظات الرئيسية. للقراءة فقط [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**الإرجاع:**  
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

يعيد مدير السمة. للقراءة فقط [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**الإرجاع:**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

يعيد نمط نص الملاحظات. للقراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**  
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

يعيد مجموعة من أدلة الرسم لشريحة الملاحظات الرئيسية. للقراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // إضافة دليل الرسم الأفقي الجديد أسفل مركز الشريحة
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)