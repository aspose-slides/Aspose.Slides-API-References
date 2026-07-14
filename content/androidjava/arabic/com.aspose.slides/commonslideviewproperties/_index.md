---
title: CommonSlideViewProperties
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل خصائص عرض الشريحة المشتركة.
type: docs
url: /ar/com.aspose.slides/commonslideviewproperties/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

يمثل خصائص عرض الشريحة المشتركة.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // تعيين خصائص العرض للعرض التقديمي
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // قيمة التكبير بالنسبة المئوية لعرض الشريحة
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // قيمة التكبير بالنسبة المئوية لعرض الملاحظات
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getScale()](#getScale--) | يحدد نسبة تكبير العرض بالنسبة المئوية. |
| [setScale(int value)](#setScale-int-) | يحدد نسبة تكبير العرض بالنسبة المئوية. |
| [getVariableScale()](#getVariableScale--) | يحدد أن محتوى العرض يجب أن يتوسع تلقائيًا ليناسب أفضل حجم النافذة الحالي. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | يحدد أن محتوى العرض يجب أن يتوسع تلقائيًا ليناسب أفضل حجم النافذة الحالي. |
| [getDrawingGuides()](#getDrawingGuides--) | إرجاع مجموعة أدلة الرسم. |
### getScale() {#getScale--}
```
public final int getScale()
```

يحدد نسبة تكبير العرض بالنسبة المئوية. قراءة/كتابة int.

**الإرجاع:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

يحدد نسبة تكبير العرض بالنسبة المئوية. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

يحدد أن محتوى العرض يجب أن يتوسع تلقائيًا ليناسب أفضل حجم النافذة الحالي. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

يحدد أن محتوى العرض يجب أن يتوسع تلقائيًا ليناسب أفضل حجم النافذة الحالي. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

إرجاع مجموعة أدلة الرسم. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // إضافة دليل الرسم العمودي الجديد إلى يمين مركز الشريحة
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // إضافة دليل الرسم الأفقي الجديد أسفل مركز الشريحة
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)