---
title: Portion
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يمثل جزءًا من النص داخل فقرة نصية.
type: docs
url: /ar/com.aspose.slides/portion/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

يمثل جزءًا من النص داخل فقرة نصية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Portion()](#Portion--) | ينشئ مثلاً جديدًا من الفئة Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | ينشئ مثلاً جديدًا من الفئة Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | ينشئ مثلاً جديدًا من الفئة Portion. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | يرجع كائن التنسيق الذي يحتوي على خصائص التنسيق المعينة صراحةً لجزء النص دون تطبيق الوراثة. |
| [getText()](#getText--) | يحصل على النص العادي للجزء أو يعيّنه. |
| [setText(String value)](#setText-java.lang.String-) | يحصل على النص العادي للجزء أو يعيّنه. |
| [getField()](#getField--) | يرجع حقلًا من هذا الجزء. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | يحوّل هذا الجزء إلى حقل يتم تحديثه تلقائيًا. |
| [addField(String internalString)](#addField-java.lang.String-) | يحوّل هذا الجزء إلى حقل يتم تحديثه تلقائيًا. |
| [removeField()](#removeField--) | يحوّل هذا الجزء الحقل إلى الجزء البسيط. |
| [getRect()](#getRect--) | يحصل على إحداثيات المستطيل الذي يحد الجزء. |
| [getCoordinates()](#getCoordinates--) | يحصل على إحداثيات بداية الجزء. |
| [getSlide()](#getSlide--) | يرجع الشريحة الأم للنص. |
| [getPresentation()](#getPresentation--) | يرجع العرض التقديمي الأم للنص. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```


ينشئ مثلاً جديدًا من الفئة Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```


ينشئ مثلاً جديدًا من الفئة Portion.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```


ينشئ مثلاً جديدًا من الفئة Portion.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```


يرجع كائن التنسيق الذي يحتوي على خصائص التنسيق المعينة صراحةً لجزء النص دون تطبيق الوراثة. قراءة فقط [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

كائن التنسيق يحتوي على معلمات التنسيق المعرفة للجزء الحالي فقط، ولا يتم تطبيق البيانات الموروثة.

للحصول على القيم الفعلية بما في ذلك الموروثة، استخدم طريقة [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**الإرجاع:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```


يحصل على النص العادي للجزء أو يعيّنه. قراءة/كتابة String.

القيمة: النص.

**الإرجاع:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يحصل على النص العادي للجزء أو يعيّنه. قراءة/كتابة String.

القيمة: النص.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```


يرجع حقلًا من هذا الجزء. قراءة فقط [IField](../../com.aspose.slides/ifield).

**الإرجاع:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```


يحويل هذا الجزء إلى حقل يتم تحديثه تلقائيًا.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```


يحويل هذا الجزء إلى حقل يتم تحديثه تلقائيًا.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| internalString | java.lang.String | الاسم الداخلي لـ FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```


يحويل هذا الجزء الحقل إلى الجزء البسيط.

### getRect() {#getRect--}
```
public final RectF getRect()
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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```


يحصل على إحداثيات بداية الجزء. إحداثي X للنقطة يمثل بداية الجزء من الحرف الأول بما في ذلك المسافة اليسرى. إحداثي Y يشمل المسافة العلوية.

**الإرجاع:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


يرجع الشريحة الأم للنص. قراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


يرجع العرض التقديمي الأم للنص. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


يرجع كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject