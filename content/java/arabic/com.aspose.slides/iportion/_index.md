---
title: IPortion
second_title: Aspose.Slides للغة Java مرجع API
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

| الطريقة | الوصف |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | يعيد كائن تنسيق يحتوي على خصائص التنسيق المحددة صراحةً لجزء النص دون تطبيق أي وراثة. |
| [getText()](#getText--) | يحصل أو يعيّن النص العادي للجزء. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يعيّن النص العادي للجزء. |
| [getField()](#getField--) | يعيد حقلًا من هذا الجزء. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | يحول هذا الجزء إلى حقل يتم تحديثه تلقائيًا. |
| [addField(String internalString)](#addField-java.lang.String-) | يحول هذا الجزء إلى حقل يتم تحديثه تلقائيًا. |
| [removeField()](#removeField--) | يحول هذا الجزء الحقل إلى الجزء البسيط. |
| [getRect()](#getRect--) | احصل على إحداثيات المستطيل الذي يحد الجزء. |
| [getCoordinates()](#getCoordinates--) | احصل على إحداثيات بداية الجزء. |

### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

يعيد كائن تنسيق يحتوي على خصائص التنسيق المحددة صراحةً لجزء النص دون تطبيق أي وراثة. للقراءة فقط [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

كائن التنسيق يحتوي على معلمات التنسيق المعرفة للجزء الحالي فقط، ولا يتم تطبيق البيانات الموروثة.

للحصول على القيم الفعلية بما في ذلك الموروثة، استخدم طريقة [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**القيمة المرجعة:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getText() {#getText--}
```
public abstract String getText()
```

يحصل أو يعيّن النص العادي للجزء. قراءة/كتابة String.

القيمة: النص.

**القيمة المرجعة:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

يحصل أو يعيّن النص العادي للجزء. قراءة/كتابة String.

القيمة: النص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```

يعيد حقلًا من هذا الجزء. للقراءة فقط [IField](../../com.aspose.slides/ifield).

**القيمة المرجعة:**
[IField](../../com.aspose.slides/ifield)

### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

يحول هذا الجزء إلى حقل يتم تحديثه تلقائيًا.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Type of field [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

يحول هذا الجزء إلى حقل يتم تحديثه تلقائيًا.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| internalString | java.lang.String | الاسم الداخلي لـ FieldTypeEx String |

### removeField() {#removeField--}
```
public abstract void removeField()
```

يحول هذا الجزء الحقل إلى الجزء البسيط.

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

احصل على إحداثيات المستطيل الذي يحد الجزء. يشمل المستطيل جميع أسطر النص في الجزء، بما في ذلك الفارغة.

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
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
java.awt.geom.Rectangle2D.Float - Rectangle that bounds portion java.awt.geom.Rectangle2D.Float

### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```

احصل على إحداثيات بداية الجزء. إحداثي X للنقطة يمثل بداية الجزء من الحرف الأول بما في ذلك الميل الجانبي الأيسر. إحداثي Y يشمل الميل العلوي.

**القيمة المرجعة:**
java.awt.geom.Point2D.Float - Coordinates of the beginning of the portion java.awt.geom.Point2D.Float