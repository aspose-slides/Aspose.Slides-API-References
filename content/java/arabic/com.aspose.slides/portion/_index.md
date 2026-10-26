---
title: Portion
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل جزءًا من النص داخل فقرة نصية.
type: docs
url: /ar/com.aspose.slides/portion/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject  
```
public class Portion implements IPortion, IDOMObject
```

يمثل جزءًا من النص داخل فقرة نصية.

## البناؤات

| البناء | الوصف |
| --- | --- |
| [Portion()](#Portion--) | ينشئ مثيًرا جديدًا من فئة Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | ينشئ مثيًرا جديدًا من فئة Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | ينشئ مثيًرا جديدًا من فئة Portion. |

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | يعيد كائن التنسيق الذي يحتوي على خصائص التنسيق المحددة صراحةً للجزء النصي دون تطبيق الوراثة. |
| [getText()](#getText--) | يحصل أو يضبط النص العادي للجزء. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يضبط النص العادي للجزء. |
| [getField()](#getField--) | يعيد حقلًا لهذا الجزء. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | يحوّل هذا الجزء إلى حقل يتم تحديثه تلقائيًا. |
| [addField(String internalString)](#addField-java.lang.String-) | يحوّل هذا الجزء إلى حقل يتم تحديثه تلقائيًا. |
| [removeField()](#removeField--) | يحوّل هذا الجزء الحقل إلى الجزء البسيط. |
| [getRect()](#getRect--) | يحصل على إحداثيات المستطيل الذي يحد الجزء. |
| [getCoordinates()](#getCoordinates--) | يحصل على إحداثيات بداية الجزء. |
| [getSlide()](#getSlide--) | يعيد الشريحة الأب للنص. |
| [getPresentation()](#getPresentation--) | يعيد العرض التقديمي الأب للنص. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Portion() {#Portion--}
```
public Portion()
```

ينشئ مثيًرا جديدًا من فئة Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

ينشئ مثيًرا جديدًا من فئة Portion.

**Parameters:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

ينشئ مثيًرا جديدًا من فئة Portion.

**Parameters:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

يعيد كائن التنسيق الذي يحتوي على خصائص التنسيق المحددة صراحةً للجزء النصي دون تطبيق الوراثة. قراءة فقط [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

كائن التنسيق يحتوي على معلمات التنسيق المعرفة للجزء الحالي فقط، ولا يتم تطبيق البيانات الموروثة.

للحصول على القيم الفعّالة بما فيها الموروثة استخدم الطريقة [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**القيمة المرجعة:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getText() {#getText--}
```
public final String getText()
```

يحصل أو يضبط النص العادي للجزء. قراءة/كتابة String.

القيمة: النص.

**القيمة المرجعة:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

يحصل أو يضبط النص العادي للجزء. قراءة/كتابة String.

القيمة: النص.

**Parameters:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

يعيد حقلًا لهذا الجزء. قراءة فقط [IField](../../com.aspose.slides/ifield).

**القيمة المرجعة:**  
[IField](../../com.aspose.slides/ifield)

### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

يحوّل هذا الجزء إلى حقل يتم تحديثه تلقائيًا.

**Parameters:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

يحوّل هذا الجزء إلى حقل يتم تحديثه تلقائيًا.

**Parameters:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| internalString | java.lang.String | الاسم الداخلي لـ FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

يحوّل هذا الجزء الحقل إلى الجزء البسيط.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

يحصل على إحداثيات المستطيل الذي يحد الجزء. المستطيل يشمل جميع أسطر النص في الجزء، بما في ذلك الفارغة.

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
java.awt.geom.Rectangle2D.Float

### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

يحصل على إحداثيات بداية الجزء. إحداثية X للنقطة تمثل بداية الجزء من الحرف الأول بما في ذلك الهامش الجانبي الأيسر. إحداثية Y تشمل الهامش العلوي.

**القيمة المرجعة:**  
java.awt.geom.Point2D.Float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأب للنص. قراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**القيمة المرجعة:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض التقديمي الأب للنص. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**  
com.aspose.slides.IDOMObject