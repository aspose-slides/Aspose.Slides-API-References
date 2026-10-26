---
title: MasterHandoutSlide
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل الشريحة الرئيسية لملفات التوزيع.
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

يمثل الشريحة الرئيسية لملفات التوزيع.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يعيد مدير HeaderFooter للشريحة الرئيسية لملفات التوزيع. |
| [getThemeManager()](#getThemeManager--) | يعيد مدير السمة. |
| [getDrawingGuides()](#getDrawingGuides--) | يعيد مجموعة من إرشادات الرسم للشريحة الرئيسية لملفات التوزيع. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها، هذه الخاصية دائمًا تُعيد false. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها، هذه الخاصية دائمًا تُعيد false. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

يعيد مدير HeaderFooter للشريحة الرئيسية لملفات التوزيع. قراءة فقط [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**القيمة المرجعة:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

يعيد مدير السمة. قراءة فقط [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**القيمة المرجعة:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

يعيد مجموعة من إرشادات الرسم للشريحة الرئيسية لملفات التوزيع. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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

**القيمة المرجعة:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)