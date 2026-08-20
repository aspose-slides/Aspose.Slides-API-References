---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: يمثل خصائص تنسيق لعناصر نص المخطط.
type: docs
url: /ar/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

يمثل خصائص تنسيق لعناصر نص المخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | يعيد أو يضبط نص الارتساء العمودي في TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | يعيد أو يضبط نص الارتساء العمودي في TextFrame. |
| [getCenterText()](#getCenterText--) | إذا كان NullableBool.True فالنص يجب أن يُوسَّط أفقياً داخل الصندوق. |
| [setCenterText(byte value)](#setCenterText-byte-) | إذا كان NullableBool.True فالنص يجب أن يُوسَّط أفقياً داخل الصندوق. |
| [getTextVerticalType()](#getTextVerticalType--) | يحدد توجيه النص. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | يحدد توجيه النص. |
| [getMarginLeft()](#getMarginLeft--) | يعيد أو يضبط الهامش الأيسر (نقاط) في TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | يعيد أو يضبط الهامش الأيسر (نقاط) في TextFrame. |
| [getMarginRight()](#getMarginRight--) | يعيد أو يضبط الهامش الأيمن (نقاط) في TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | يعيد أو يضبط الهامش الأيمن (نقاط) في TextFrame. |
| [getMarginTop()](#getMarginTop--) | يعيد أو يضبط الهامش العلوي (نقاط) في TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | يعيد أو يضبط الهامش العلوي (نقاط) في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | يعيد أو يضبط الهامش السفلي (نقاط) في TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | يعيد أو يضبط الهامش السفلي (نقاط) في TextFrame. |
| [getWrapText()](#getWrapText--) | صحيح إذا تم لف النص عند هوامش TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | صحيح إذا تم لف النص عند هوامش TextFrame. |
| [getAutofitType()](#getAutofitType--) | يعيد أو يضبط وضعية الملاءمة التلقائية للنص. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | يعيد أو يضبط وضعية الملاءمة التلقائية للنص. |
| [getRotationAngle()](#getRotationAngle--) | يحدد الدوران المخصص الذي يُطبق على النص داخل الصندوق المحدد. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | يحدد الدوران المخصص الذي يُطبق على النص داخل الصندوق المحدد. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

يعيد أو يضبط نص الارتساء العمودي في TextFrame. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**القيمة المرجعة:**  
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

يعيد أو يضبط نص الارتساء العمودي في TextFrame. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

إذا كان NullableBool.True فالنص يجب أن يُوسَّط أفقياً داخل الصندوق. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**  
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

إذا كان NullableBool.True فالنص يجب أن يُوسَّط أفقياً داخل الصندوق. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

يحدد توجيه النص. القيمة الناتجة من دوران النص البصري تُلخص من هذه الخاصية والزاوية المخصصة في الخاصية RotationAngle. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**القيمة المرجعة:**  
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

يحدد توجيه النص. القيمة الناتجة من دوران النص البصري تُلخص من هذه الخاصية والزاوية المخصصة في الخاصية RotationAngle. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

يعيد أو يضبط الهامش الأيسر (نقاط) في TextFrame. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**القيمة المرجعة:**  
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

يعيد أو يضبط الهامش الأيسر (نقاط) في TextFrame. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

يعيد أو يضبط الهامش الأيمن (نقاط) في TextFrame. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**القيمة المرجعة:**  
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

يعيد أو يضبط الهامش الأيمن (نقاط) في TextFrame. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

يعيد أو يضبط الهامش العلوي (نقاط) في TextFrame. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**القيمة المرجعة:**  
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

يعيد أو يضبط الهامش العلوي (نقاط) في TextFrame. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

يعيد أو يضبط الهامش السفلي (نقاط) في TextFrame. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**القيمة المرجعة:**  
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

يعيد أو يضبط الهامش السفلي (نقاط) في TextFrame. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة double.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

صحيح إذا تم لف النص عند هوامش TextFrame. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2007/2013). قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**  
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

صحيح إذا تم لف النص عند هوامش TextFrame. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2007/2013). قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

يعيد أو يضبط وضعية الملاءمة التلقائية للنص. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة [TextAutofitType](../../com.aspose.slides/textautofittype).

**القيمة المرجعة:**  
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

يعيد أو يضبط وضعية الملاءمة التلقائية للنص. تغيير هذه الخاصية يمكن أن ينتج تأثيراً معيناً فقط لهذه أجزاء المخطط: DataLabel و DataLabelFormat (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة/كتابة [TextAutofitType](../../com.aspose.slides/textautofittype).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

يحدد الدوران المخصص الذي يُطبق على النص داخل الصندوق المحدد. إذا لم يُحدد، يُستخدم دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران بالإضافة إلى أن النص نفسه لديه دوران مطبق. القيمة الناتجة من دوران النص البصري تُلخص من هذه الخاصية والنوع العمودي المحدد مسبقاً في الخاصية TextVerticalType. قراءة/كتابة float.

--------------------

> ```
> اعتبر الحالة التي يكون فيها الشكل مُطبق عليه دوران قدره 90 درجة باتجاه عقارب الساعة. 
>  وبالإضافة إلى ذلك، يحتوي جسم النص نفسه على دوران قدره -90 درجة 
>  عكس اتجاه عقارب الساعة مُطبق عليه. ثم سيظهر الشكل الناتج كما لو كان
>  مُدوَّرًا لكن النص داخل الشكل سيظهر كما لو أنه لم يُدوَّر مطلقًا.
> ```


**القيمة المرجعة:**  
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

يحدد الدوران المخصص الذي يُطبق على النص داخل الصندوق المحدد. إذا لم يُحدد، يُستخدم دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران بالإضافة إلى أن النص نفسه لديه دوران مطبق. القيمة الناتجة من دوران النص البصري تُلخص من هذه الخاصية والنوع العمودي المحدد مسبقاً في الخاصية TextVerticalType. قراءة/كتابة float.

--------------------

> ```
> اعتبر الحالة التي يكون فيها الشكل مُطبق عليه دوران قدره 90 درجة باتجاه عقارب الساعة.
>  بالإضافة إلى ذلك، يحتوي جسم النص نفسه على دوران قدره -90 درجة
>  عكس اتجاه عقارب الساعة مُطبق عليه. ثم سيظهر الشكل الناتج كما لو كان
>  مُدوَّرًا لكن النص داخل الشكل سيظهر كما لو أنه لم يُدوَّر مطلقًا.
> ```

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |