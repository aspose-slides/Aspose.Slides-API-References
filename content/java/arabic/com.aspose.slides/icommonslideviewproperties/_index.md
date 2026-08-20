---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Java API Reference
description: يمثل خصائص عرض الشريحة الشائعة.
type: docs
url: /ar/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

يمثل خصائص عرض الشريحة الشائعة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getScale()](#getScale--) | يحدد نسبة مقياس العرض بالنسب المئوية. |
| [setScale(int value)](#setScale-int-) | يحدد نسبة مقياس العرض بالنسب المئوية. |
| [getVariableScale()](#getVariableScale--) | يحدد أن محتوى العرض يجب أن يُقاس تلقائيًا ليناسب أفضل حجم للنافذة الحالية. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | يحدد أن محتوى العرض يجب أن يُقاس تلقائيًا ليناسب أفضل حجم للنافذة الحالية. |
| [getDrawingGuides()](#getDrawingGuides--) | يرجع مجموعة أدلة الرسم. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

يحدد نسبة مقياس العرض بالنسب المئوية. قراءة/كتابة int.

**القيمة المرجعة:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

يحدد نسبة مقياس العرض بالنسب المئوية. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

يحدد أن محتوى العرض يجب أن يُقاس تلقائيًا ليناسب أفضل حجم للنافذة الحالية. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

يحدد أن محتوى العرض يجب أن يُقاس تلقائيًا ليناسب أفضل حجم للنافذة الحالية. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

يرجع مجموعة أدلة الرسم. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
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


**القيمة المرجعة:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)