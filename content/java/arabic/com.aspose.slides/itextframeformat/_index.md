---
title: ITextFrameFormat
second_title: Aspose.Slides لمرجع API جافا
description: يحتوي على خصائص تنسيق إطارات النص.
type: docs
url: /ar/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

يحتوي على خصائص تنسيق TextFrame.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | إرجاع style النص. |
| [getMarginLeft()](#getMarginLeft--) | إرجاع أو تعيين الهامش الأيسر (نقاط) في TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | إرجاع أو تعيين الهامش الأيسر (نقاط) في TextFrame. |
| [getMarginRight()](#getMarginRight--) | إرجاع أو تعيين الهامش الأيمن (نقاط) في TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | إرجاع أو تعيين الهامش الأيمن (نقاط) في TextFrame. |
| [getMarginTop()](#getMarginTop--) | إرجاع أو تعيين الهامش العلوي (نقاط) في TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | إرجاع أو تعيين الهامش العلوي (نقاط) في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | إرجاع أو تعيين الهامش السفلي (نقاط) في TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | إرجاع أو تعيين الهامش السفلي (نقاط) في TextFrame. |
| [getWrapText()](#getWrapText--) | صحيح إذا تم التفاف النص عند هوامش TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | صحيح إذا تم التفاف النص عند هوامش TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | إرجاع أو تعيين النص العمودي في TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | إرجاع أو تعيين النص العمودي في TextFrame. |
| [getCenterText()](#getCenterText--) | إذا كان NullableBool.True فإن النص يجب أن يتم توسيطه أفقيًا داخل الصندوق. |
| [setCenterText(byte value)](#setCenterText-byte-) | إذا كان NullableBool.True فإن النص يجب أن يتم توسيطه أفقيًا داخل الصندوق. |
| [getTextVerticalType()](#getTextVerticalType--) | يحدد اتجاه النص. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | يحدد اتجاه النص. |
| [getAutofitType()](#getAutofitType--) | إرجاع أو تعيين وضع autofit للنص. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | إرجاع أو تعيين وضع autofit للنص. |
| [getColumnCount()](#getColumnCount--) | إرجاع أو تعيين عدد الأعمدة في مساحة النص. |
| [setColumnCount(int value)](#setColumnCount-int-) | إرجاع أو تعيين عدد الأعمدة في مساحة النص. |
| [getColumnSpacing()](#getColumnSpacing--) | إرجاع أو تعيين المسافة بين أعمدة النص في مساحة النص (نقاط). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | إرجاع أو تعيين المسافة بين أعمدة النص في مساحة النص (نقاط). |
| [getThreeDFormat()](#getThreeDFormat--) | إرجاع كائن ThreeDFormat الذي يمثل خصائص التأثير ثلاثي الأبعاد للنص. |
| [getKeepTextFlat()](#getKeepTextFlat--) | إرجاع أو تعيين إبقاء النص خارج مشهد 3D تمامًا. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | إرجاع أو تعيين إبقاء النص خارج مشهد 3D تمامًا. |
| [getRotationAngle()](#getRotationAngle--) | يحدد الدوران المخصص المطبق على النص داخل الصندوق المحدد. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | يحدد الدوران المخصص المطبق على النص داخل الصندوق المحدد. |
| [getTransform()](#getTransform--) | الحصول أو تعيين شكل التفاف النص. |
| [setTransform(byte value)](#setTransform-byte-) | الحصول أو تعيين شكل التفاف النص. |
| [getEffective()](#getEffective--) | الحصول على بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

إرجاع style النص. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

إرجاع أو تعيين الهامش الأيسر (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

إرجاع أو تعيين الهامش الأيسر (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

إرجاع أو تعيين الهامش الأيمن (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

إرجاع أو تعيين الهامش الأيمن (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

إرجاع أو تعيين الهامش العلوي (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

إرجاع أو تعيين الهامش العلوي (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

إرجاع أو تعيين الهامش السفلي (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

إرجاع أو تعيين الهامش السفلي (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

صحيح إذا تم التفاف النص عند هوامش TextFrame. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

صحيح إذا تم التفاف النص عند هوامش TextFrame. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

إرجاع أو تعيين النص العمودي في TextFrame. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**الإرجاع:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

إرجاع أو تعيين النص العمودي في TextFrame. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

إذا كان NullableBool.True فإن النص يجب أن يتم توسيطه أفقيًا داخل الصندوق. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

إذا كان NullableBool.True فإن النص يجب أن يتم توسيطه أفقيًا داخل الصندوق. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

يحدد اتجاه النص. القيمة الناتجة من دوران النص البصري يتم تلخيصها من هذه الخاصية والزاوية المخصصة في خاصية RotationAngle. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**الإرجاع:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

يحدد اتجاه النص. القيمة الناتجة من دوران النص البصري يتم تلخيصها من هذه الخاصية والزاوية المخصصة في خاصية RotationAngle. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

إرجاع أو تعيين وضع autofit للنص. قراءة/كتابة [TextAutofitType](../../com.aspose.slides/textautofittype).

**الإرجاع:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

إرجاع أو تعيين وضع autofit للنص. قراءة/كتابة [TextAutofitType](../../com.aspose.slides/textautofittype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

إرجاع أو تعيين عدد الأعمدة في مساحة النص. يجب أن تكون هذه القيمة رقمًا إيجابيًا. وإلا سيُضبط الصفر. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة int.

**الإرجاع:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

إرجاع أو تعيين عدد الأعمدة في مساحة النص. يجب أن تكون هذه القيمة رقمًا إيجابيًا. وإلا سيُضبط الصفر. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

إرجاع أو تعيين المسافة بين أعمدة النص في مساحة النص (نقاط). يجب أن يُطبق فقط عندما يكون هناك أكثر من عمود واحد. يجب أن تكون هذه القيمة رقمًا إيجابيًا. وإلا سيُضبط الصفر. قراءة/كتابة double.

**الإرجاع:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

إرجاع أو تعيين المسافة بين أعمدة النص في مساحة النص (نقاط). يجب أن يُطبق فقط عندما يكون هناك أكثر من عمود واحد. يجب أن تكون هذه القيمة رقمًا إيجابيًا. وإلا سيُضبط الصفر. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

إرجاع كائن ThreeDFormat الذي يمثل خصائص التأثير ثلاثي الأبعاد للنص. قراءة فقط [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // تعيين تحويل النص
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // تعيين البثق
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // تعيين الخط الخارجي
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // تعيين العمق
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // تعيين المادة
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // تعيين الإضاءة
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // تعيين نوع الكاميرا
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

إرجاع أو تعيين إبقاء النص خارج مشهد 3D تمامًا. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

إرجاع أو تعيين إبقاء النص خارج مشهد 3D تمامًا. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

يحدد الدوران المخصص المطبق على النص داخل الصندوق المحدد. إذا لم يُحدد، تُستخدم دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل قد يُطبق عليه دوران بالإضافة إلى دوران النص نفسه. القيمة الناتجة من دوران النص البصري تُلخّص من هذه الخاصية والنوع العمودي المحدد مسبقًا في خاصية TextVerticalType. قراءة/كتابة float.

--------------------

> ```
> اعتبر الحالة التي يكون فيها الشكل مع تطبيق دوران قدره 90 درجة باتجاه عقارب الساعة. 
>  بالإضافة إلى ذلك، يحتوي نص الجسم نفسه على دوران قدره -90 درجة 
>  عكس اتجاه عقارب الساعة مطبقًا عليه. ثم سيظهر الشكل الناتج كأنه مدور ولكن النص بداخله سيظهر كما لو أنه لم يتم تدويره على الإطلاق.
> ```


**الإرجاع:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

يحدد الدوران المخصص المطبق على النص داخل الصندوق المحدد. إذا لم يُحدد، تُستخدم دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل قد يُطبق عليه دوران بالإضافة إلى دوران النص نفسه. القيمة الناتجة من دوران النص البصري تُلخّص من هذه الخاصية والنوع العمودي المحدد مسبقًا في خاصية TextVerticalType. قراءة/كتابة float.

--------------------

> ```
> اعتبر الحالة التي يكون فيها الشكل مع تطبيق دوران قدره 90 درجة باتجاه عقارب الساعة. 
>  بالإضافة إلى ذلك، يحتوي نص الجسم نفسه على دوران قدره -90 درجة عكس اتجاه عقارب الساعة مطبقًا عليه. ثم سيظهر الشكل الناتج كأنه
>  مدور ولكن النص بداخله سيظهر كما لو أنه لم يتم تدويره على الإطلاق.
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

الحصول أو تعيين شكل التفاف النص. قراءة/كتابة [TextShapeType](../../com.aspose.slides/textshapetype).

**الإرجاع:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

الحصول أو تعيين شكل التفاف النص. قراءة/كتابة [TextShapeType](../../com.aspose.slides/textshapetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

الحصول على بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).