---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android عبر مرجع API لل Java
description: يمثل خصائص تنسيق لعناصر نص المخطط.
type: docs
url: /ar/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

يمثل خصائص تنسيق لعناصر نص المخطط.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | إرجاع أو ضبط نص التثبيت العمودي في TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | إرجاع أو ضبط نص التثبيت العمودي في TextFrame. |
| [getCenterText()](#getCenterText--) | إذا كان NullableBool.True فإن النص يجب أن يكون مركّزًا أفقياً داخل الصندوق. |
| [setCenterText(byte value)](#setCenterText-byte-) | إذا كان NullableBool.True فإن النص يجب أن يكون مركّزًا أفقياً داخل الصندوق. |
| [getTextVerticalType()](#getTextVerticalType--) | تحديد اتجاه النص. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | تحديد اتجاه النص. |
| [getMarginLeft()](#getMarginLeft--) | إرجاع أو ضبط الهامش الأيسر (نقاط) في TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | إرجاع أو ضبط الهامش الأيسر (نقاط) في TextFrame. |
| [getMarginRight()](#getMarginRight--) | إرجاع أو ضبط الهامش الأيمن (نقاط) في TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | إرجاع أو ضبط الهامش الأيمن (نقاط) في TextFrame. |
| [getMarginTop()](#getMarginTop--) | إرجاع أو ضبط الهامش العلوي (نقاط) في TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | إرجاع أو ضبط الهامش العلوي (نقاط) في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | إرجاع أو ضبط الهامش السفلي (نقاط) في TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | إرجاع أو ضبط الهامش السفلي (نقاط) في TextFrame. |
| [getWrapText()](#getWrapText--) | صحيح إذا تم لف النص عند حدود TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | صحيح إذا تم لف النص عند حدود TextFrame. |
| [getAutofitType()](#getAutofitType--) | إرجاع أو ضبط وضع الملاءمة التلقائية للنص. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | إرجاع أو ضبط وضع الملاءمة التلقائية للنص. |
| [getRotationAngle()](#getRotationAngle--) | تحديد الدوران المخصص الذي يُطبق على النص داخل الصندوق المحيط. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | تحديد الدوران المخصص الذي يُطبق على النص داخل الصندوق المحيط. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

إرجاع أو ضبط نص التثبيت العمودي في TextFrame. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**الإرجاع:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

إرجاع أو ضبط نص التثبيت العمودي في TextFrame. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

إذا كان NullableBool.True فإن النص يجب أن يكون مركّزًا أفقياً داخل الصندوق. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

إذا كان NullableBool.True فإن النص يجب أن يكون مركّزًا أفقياً داخل الصندوق. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

تحديد اتجاه النص. القيمة الناتجة لدوران النص البصري ملخصة من هذه الخاصية والزاوية المخصصة في الخاصية RotationAngle. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**الإرجاع:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

تحديد اتجاه النص. القيمة الناتجة لدوران النص البصري ملخصة من هذه الخاصية والزاوية المخصصة في الخاصية RotationAngle. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

إرجاع أو ضبط الهامش الأيسر (نقاط) في TextFrame. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**الإرجاع:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

إرجاع أو ضبط الهامش الأيسر (نقاط) في TextFrame. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

إرجاع أو ضبط الهامش الأيمن (نقاط) في TextFrame. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**الإرجاع:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

إرجاع أو ضبط الهامش الأيمن (نقاط) في TextFrame. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

إرجاع أو ضبط الهامش العلوي (نقاط) في TextFrame. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**الإرجاع:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

إرجاع أو ضبط الهامش العلوي (نقاط) في TextFrame. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

إرجاع أو ضبط الهامش السفلي (نقاط) في TextFrame. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**الإرجاع:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

إرجاع أو ضبط الهامش السفلي (نقاط) في TextFrame. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

صحيح إذا تم لف النص عند حدود TextFrame. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2007/2013). قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

صحيح إذا تم لف النص عند حدود TextFrame. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2007/2013). قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

إرجاع أو ضبط وضع الملاءمة التلقائية للنص. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة [TextAutofitType](../../com.aspose.slides/textautofittype).

**الإرجاع:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

إرجاع أو ضبط وضع الملاءمة التلقائية للنص. تعديل هذه الخاصية يمكن أن يؤثر فقط على أجزاء المخطط التالية: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة [TextAutofitType](../../com.aspose.slides/textautofittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

تحديد الدوران المخصص الذي يُطبق على النص داخل الصندوق المحيط. إذا لم يُحدد، يتم استخدام دوران الشكل المصاحب. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران إضافي إلى جانب أن النص نفسه لديه دوران يُطبق عليه. القيمة الناتجة لدوران النص البصري ملخصة من هذه الخاصية والنوع العمودي المحدد مسبقًا في الخاصية TextVerticalType. قراءة/كتابة float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**الإرجاع:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

تحديد الدوران المخصص الذي يُطبق على النص داخل الصندوق المحيط. إذا لم يُحدد، يتم استخدام دوران الشكل المصاحب. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران إضافي إلى جانب أن النص نفسه لديه دوران يُطبق عليه. القيمة الناتجة لدوران النص البصري ملخصة من هذه الخاصية والنوع العمودي المحدد مسبقًا في الخاصية TextVerticalType. قراءة/كتابة float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |