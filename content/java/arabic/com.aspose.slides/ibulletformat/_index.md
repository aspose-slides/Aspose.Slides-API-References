---
title: IBulletFormat
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل خصائص تنسيق نقط الفقرة.
type: docs
url: /ar/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

يمثل خصائص تنسيق نقط الفقرة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | إرجاع أو تعيين نوع الرصاصة للفقرة دون وراثة. |
| [setType(byte value)](#setType-byte-) | إرجاع أو تعيين نوع الرصاصة للفقرة دون وراثة. |
| [getChar()](#getChar--) | إرجاع أو تعيين حرف الرصاصة للفقرة دون وراثة. |
| [setChar(char value)](#setChar-char-) | إرجاع أو تعيين حرف الرصاصة للفقرة دون وراثة. |
| [getFont()](#getFont--) | إرجاع أو تعيين خط الرصاصة للفقرة دون وراثة. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين خط الرصاصة للفقرة دون وراثة. |
| [getHeight()](#getHeight--) | إرجاع أو تعيين ارتفاع الرصاصة للفقرة دون وراثة. |
| [setHeight(float value)](#setHeight-float-) | إرجاع أو تعيين ارتفاع الرصاصة للفقرة دون وراثة. |
| [getColor()](#getColor--) | إرجاع تنسيق اللون للرصاصة في الفقرة دون وراثة. |
| [getPicture()](#getPicture--) | إرجاع الصورة المستخدمة كرصاصة في الفقرة دون وراثة. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | إرجاع أو تعيين الرقم الأول المستخدم لمجموعة من الرصاصات المرقمة دون وراثة. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | إرجاع أو تعيين الرقم الأول المستخدم لمجموعة من الرصاصات المرقمة دون وراثة. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | إرجاع أو تعيين نمط الرصاصة المرقمة دون وراثة. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | إرجاع أو تعيين نمط الرصاصة المرقمة دون وراثة. |
| [isBulletHardColor()](#isBulletHardColor--) | تحديد ما إذا كانت الرصاصة لها لون خاص أو ترثه من الجزء الأول في الفقرة. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | تحديد ما إذا كانت الرصاصة لها لون خاص أو ترثه من الجزء الأول في الفقرة. |
| [isBulletHardFont()](#isBulletHardFont--) | تحديد ما إذا كانت الرصاصة لها خط خاص أو ترثه من الجزء الأول في الفقرة. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | تحديد ما إذا كانت الرصاصة لها خط خاص أو ترثه من الجزء الأول في الفقرة. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | تعيين إزاحات غير صفرية افتراضية للخاصيتين Indent و MarginLeft للفقرة الفعّالة عندما تكون الرصاصات مفعّلة (كما يفعل PowerPoint عند تمكين نقط الفقرة/التعداد). |
| [getEffective()](#getEffective--) | الحصول على بيانات تنسيق الرصاص الفعّالة مع تطبيق الوراثة. |
### getType() {#getType--}
```
public abstract byte getType()
```

إرجاع أو تعيين نوع الرصاصة للفقرة دون وراثة. قراءة/كتابة [BulletType](../../com.aspose.slides/bullettype).

**الإرجاع:**  
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

إرجاع أو تعيين نوع الرصاصة للفقرة دون وراثة. قراءة/كتابة [BulletType](../../com.aspose.slides/bullettype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

إرجاع أو تعيين حرف الرصاصة للفقرة دون وراثة. قراءة/كتابة char.

**الإرجاع:**  
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

إرجاع أو تعيين حرف الرصاصة للفقرة دون وراثة. قراءة/كتابة char.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

إرجاع أو تعيين خط الرصاصة للفقرة دون وراثة. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**  
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

إرجاع أو تعيين خط الرصاصة للفقرة دون وراثة. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

إرجاع أو تعيين ارتفاع الرصاصة للفقرة دون وراثة. القيمة Float.NaN تحدد أن الرصاصة ترث الارتفاع من الجزء الأول في الفقرة. قراءة/كتابة float.

**الإرجاع:**  
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

إرجاع أو تعيين ارتفاع الرصاصة للفقرة دون وراثة. القيمة Float.NaN تحدد أن الرصاصة ترث الارتفاع من الجزء الأول في الفقرة. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

إرجاع تنسيق اللون للرصاصة في الفقرة دون وراثة. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

إرجاع الصورة المستخدمة كرصاصة في الفقرة دون وراثة. قراءة فقط [ISlidesPicture](../../com.aspose.slides/islidespicture).

**الإرجاع:**  
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

إرجاع أو تعيين الرقم الأول المستخدم لمجموعة من الرصاصات المرقمة دون وراثة. قراءة/كتابة short.

**الإرجاع:**  
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

إرجاع أو تعيين الرقم الأول المستخدم لمجموعة من الرصاصات المرقمة دون وراثة. قراءة/كتابة short.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

إرجاع أو تعيين نمط الرصاصة المرقمة دون وراثة. قراءة/كتابة [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**الإرجاع:**  
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

إرجاع أو تعيين نمط الرصاصة المرقمة دون وراثة. قراءة/كتابة [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

تحديد ما إذا كانت الرصاصة لها لون خاص أو ترثه من الجزء الأول في الفقرة. **NullableBool#True** إذا كانت الرصاصة لها لون خاص و **NullableBool#False** إذا كانت الرصاصة ترث اللون من الجزء الأول في الفقرة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

تحديد ما إذا كانت الرصاصة لها لون خاص أو ترثه من الجزء الأول في الفقرة. **NullableBool#True** إذا كانت الرصاصة لها لون خاص و **NullableBool#False** إذا كانت الرصاصة ترث اللون من الجزء الأول في الفقرة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

تحديد ما إذا كانت الرصاصة لها خط خاص أو ترثه من الجزء الأول في الفقرة. **NullableBool#True** إذا كانت الرصاصة لها خط خاص و **NullableBool#False** إذا كانت الرصاصة ترث الخط من الجزء الأول في الفقرة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

تحديد ما إذا كانت الرصاصة لها خط خاص أو ترثه من الجزء الأول في الفقرة. **NullableBool#True** إذا كانت الرصاصة لها خط خاص و **NullableBool#False** إذا كانت الرصاصة ترث الخط من الجزء الأول في الفقرة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

تعيين إزاحات غير صفرية افتراضية للخاصيتين Indent و MarginLeft للفقرة الفعّالة عندما تكون الرصاصات مفعّلة (كما يفعل PowerPoint عند تمكين نقط الفقرة/التعداد). إذا تم تعطيل الرصاصات يتم فقط إعادة تعيين Indent و MarginLeft للفقرة (كما يفعل PowerPoint عند تعطيل نقط الفقرة/التعداد). تُطبَّق إزاحات الفراغات بالنسبة إلى سياق الرصاصة الحالي - IBulletFormat.Type، .NumberedBulletStyle و FontHeight للجزء الأول. تُطبَّق إزاحات غير الصفر للـ Indent و MarginLeft الفعّالين للفقرة الحالية (لتصبح القيم الناتجة قيمًا محلية).
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

الحصول على بيانات تنسيق الرصاصة الفعّالة مع تطبيق الوراثة.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**  
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).