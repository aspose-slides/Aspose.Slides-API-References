---
title: IPortion
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يمثل جزءًا من النص داخل فقرة نصية.
type: docs
url: /ar/com.aspose.slides/iportion/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

يمثل جزءًا من النص داخل فقرة نصية.
## الطرق

| Method | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | يرجع كائن تنسيق يحتوي على خصائص التنسيق المعينة صراحة للجزء النصي دون تطبيق الوراثة. |
| [getText()](#getText--) | يحصل أو يضبط النص العادي لجزء. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يضبط النص العادي لجزء. |
| [getField()](#getField--) | يرجع حقلًا لهذا الجزء. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | يحول هذا الجزء إلى حقل يُحدّث تلقائيًا. |
| [addField(String internalString)](#addField-java.lang.String-) | يحول هذا الجزء إلى حقل يُحدّث تلقائيًا. |
| [removeField()](#removeField--) | يحول هذا الجزء الحقل إلى جزء بسيط. |
| [getRect()](#getRect--) | يحصل على إحداثيات المستطيل الذي يحدّ الجزء. |
| [getCoordinates()](#getCoordinates--) | يحصل على إحداثيات بداية الجزء. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

يرجع كائن تنسيق يحتوي على خصائص التنسيق المعينة صراحة للجزء النصي دون تطبيق الوراثة. قراءة فقط [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

كائن التنسيق يحتوي على معلمات التنسيق المحددة للجزء الحالي فقط، ولا يتم تطبيق البيانات الموروثة.

للحصول على القيم الفعّالة بما في ذلك الموروثة استخدم طريقة [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**الإرجاع:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

يحصل أو يضبط النص العادي لجزء. قراءة/كتابة String.

القيمة: النص.

**الإرجاع:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

يحصل أو يضبط النص العادي لجزء. قراءة/كتابة String.

القيمة: النص.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```

يرجع حقلًا لهذا الجزء. قراءة فقط [IField](../../com.aspose.slides/ifield).

**الإرجاع:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

يحول هذا الجزء إلى حقل يُحدّث تلقائيًا.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | نوع الحقل [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

يحول هذا الجزء إلى حقل يُحدّث تلقائيًا.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| internalString | java.lang.String | الاسم الداخلي لسلسلة FieldTypeEx String |

### removeField() {#removeField--}
```
public abstract void removeField()
```

يحول هذا الجزء الحقل إلى جزء بسيط.

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

يحصل على إحداثيات المستطيل الذي يحدّ الجزء. المستطيل يشمل جميع سطور النص في الجزء، بما في ذلك السطور الفارغة.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
android.graphics.RectF - مستطيل يحدّ الجزء android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

يحصل على إحداثيات بداية الجزء. إحداثي X للنقطة يمثل بداية الجزء من الحرف الأول بما في ذلك الهامش الجانبي الأيسر. إحداثي Y يشمل الهامش العلوي.

**الإرجاع:**
android.graphics.PointF - إحداثيات بداية الجزء android.graphics.PointF