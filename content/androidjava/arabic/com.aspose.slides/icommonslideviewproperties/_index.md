---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل خصائص عرض الشريحة العامة.
type: docs
url: /ar/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

يمثل خصائص عرض الشريحة العامة.
## Methods

| الطريقة | الوصف |
| --- | --- |
| [getScale()](#getScale--) | يحدد نسبة مقياس العرض بالنسبة المئوية. |
| [setScale(int value)](#setScale-int-) | يحدد نسبة مقياس العرض بالنسبة المئوية. |
| [getVariableScale()](#getVariableScale--) | يحدد أنه يجب أن يتم ضبط محتوى العرض تلقائيًا ليتناسب بأفضل شكل مع حجم النافذة الحالي. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | يحدد أنه يجب أن يتم ضبط محتوى العرض تلقائيًا ليتناسب بأفضل شكل مع حجم النافذة الحالي. |
| [getDrawingGuides()](#getDrawingGuides--) | يرجع مجموعة إرشادات الرسم. |
### getScale() {#getScale--}
```
public abstract int getScale()
```


يحدد نسبة مقياس العرض بالنسبة المئوية. قراءة/كتابة int.

**الإرجاع:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


يحدد نسبة مقياس العرض بالنسبة المئوية. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


يحدد أنه يجب أن يتم ضبط محتوى العرض تلقائيًا ليتناسب بأفضل شكل مع حجم النافذة الحالي. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


يحدد أنه يجب أن يتم ضبط محتوى العرض تلقائيًا ليتناسب بأفضل شكل مع حجم النافذة الحالي. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


يرجع مجموعة إرشادات الرسم. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
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