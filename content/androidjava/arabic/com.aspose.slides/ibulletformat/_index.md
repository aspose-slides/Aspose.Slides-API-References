---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /ar/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

يمثِّل خصائص تنسيق العلامة النقطية للفقرة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | تُرجع أو تُعيّن نوع العلامة النقطية لفقرة بدون وراثة. |
| [setType(byte value)](#setType-byte-) | تُرجع أو تُعيّن نوع العلامة النقطية لفقرة بدون وراثة. |
| [getChar()](#getChar--) | تُرجع أو تُعيّن الحرف النقطي لفقرة بدون وراثة. |
| [setChar(char value)](#setChar-char-) | تُرجع أو تُعيّن الحرف النقطي لفقرة بدون وراثة. |
| [getFont()](#getFont--) | تُرجع أو تُعيّن خط العلامة النقطية لفقرة بدون وراثة. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | تُرجع أو تُعيّن خط العلامة النقطية لفقرة بدون وراثة. |
| [getHeight()](#getHeight--) | تُرجع أو تُعيّن ارتفاع العلامة النقطية لفقرة بدون وراثة. |
| [setHeight(float value)](#setHeight-float-) | تُرجع أو تُعيّن ارتفاع العلامة النقطية لفقرة بدون وراثة. |
| [getColor()](#getColor--) | تُرجع تنسيق اللون للعلامة النقطية لفقرة بدون وراثة. |
| [getPicture()](#getPicture--) | تُرجع الصورة المستخدمة كعلامة نقطية في فقرة بدون وراثة. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | تُرجع أو تُعيّن أول رقم يُستَخدم لمجموعة العلامات المرقَّمة بدون وراثة. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | تُرجع أو تُعيّن أول رقم يُستَخدم لمجموعة العلامات المرقَّمة بدون وراثة. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | تُرجع أو تُعيّن نمط العلامة المرقَّمة بدون وراثة. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | تُرجع أو تُعيّن نمط العلامة المرقَّمة بدون وراثة. |
| [isBulletHardColor()](#isBulletHardColor--) | يحدِّد ما إذا كان للعلامة لون خاص أم يتم وراثته من الجزء الأول في الفقرة. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | يحدِّد ما إذا كان للعلامة لون خاص أم يتم وراثته من الجزء الأول في الفقرة. |
| [isBulletHardFont()](#isBulletHardFont--) | يحدِّد ما إذا كان للعلامة خط خاص أم يتم وراثته من الجزء الأول في الفقرة. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | يحدِّد ما إذا كان للعلامة خط خاص أم يتم وراثته من الجزء الأول في الفقرة. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | يضبط الإزاحات غير الصفرية الافتراضية للهوامش الفعلية للفقرة (Indent وMarginLeft) عندما تكون العلامات مفعَّلة (كما يفعل PowerPoint عند تمكين العلامات/الترقيم). |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق العلامة الفعلية مع تطبيق الوراثة. |
### getType() {#getType--}
```
public abstract byte getType()
```

تُرجع أو تُعيّن نوع العلامة النقطية لفقرة بدون وراثة. قراءة/كتابة [BulletType](../../com.aspose.slides/bullettype).

**الإرجاع:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

تُرجع أو تُعيّن نوع العلامة النقطية لفقرة بدون وراثة. قراءة/كتابة [BulletType](../../com.aspose.slides/bullettype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

تُرجع أو تُعيّن الحرف النقطي لفقرة بدون وراثة. قراءة/كتابة char.

**الإرجاع:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

تُرجع أو تُعيّن الحرف النقطي لفقرة بدون وراثة. قراءة/كتابة char.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

تُرجع أو تُعيّن خط العلامة النقطية لفقرة بدون وراثة. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

تُرجع أو تُعيّن خط العلامة النقطية لفقرة بدون وراثة. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

تُرجع أو تُعيّن ارتفاع العلامة النقطية لفقرة بدون وراثة. القيمة Float.NaN تحدد أن العلامة ترث الارتفاع من الجزء الأول في الفقرة. قراءة/كتابة float.

**الإرجاع:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

تُرجع أو تُعيّن ارتفاع العلامة النقطية لفقرة بدون وراثة. القيمة Float.NaN تحدد أن العلامة ترث الارتفاع من الجزء الأول في الفقرة. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

تُرجع تنسيق اللون للعلامة النقطية لفقرة بدون وراثة. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

تُرجع الصورة المستخدمة كعلامة نقطية في فقرة بدون وراثة. قراءة فقط [ISlidesPicture](../../com.aspose.slides/islidespicture).

**الإرجاع:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

تُرجع أو تُعيّن أول رقم يُستَخدم لمجموعة العلامات المرقَّمة بدون وراثة. قراءة/كتابة short.

**الإرجاع:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

تُرجع أو تُعيّن أول رقم يُستَخدم لمجموعة العلامات المرقَّمة بدون وراثة. قراءة/كتابة short.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

تُرجع أو تُعيّن نمط العلامة المرقَّمة بدون وراثة. قراءة/كتابة [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**الإرجاع:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

تُرجع أو تُعيّن نمط العلامة المرقَّمة بدون وراثة. قراءة/كتابة [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

يحدِّد ما إذا كان للعلامة لون خاص أم يتم وراثته من الجزء الأول في الفقرة. **NullableBool\#True** إذا كان للعلامة لون خاص و**NullableBool\#False** إذا كانت وراثة اللون من الجزء الأول في الفقرة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

يحدِّد ما إذا كان للعلامة لون خاص أم يتم وراثته من الجزء الأول في الفقرة. **NullableBool\#True** إذا كان للعلامة لون خاص و**NullableBool\#False** إذا كانت وراثة اللون من الجزء الأول في الفقرة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

يحدِّد ما إذا كان للعلامة خط خاص أم يتم وراثته من الجزء الأول في الفقرة. **NullableBool\#True** إذا كان للعلامة خط خاص و**NullableBool\#False** إذا كانت وراثة الخط من الجزء الأول في الفقرة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

يحدِّد ما إذا كان للعلامة خط خاص أم يتم وراثته من الجزء الأول في الفقرة. **NullableBool\#True** إذا كان للعلامة خط خاص و**NullableBool\#False** إذا كانت وراثة الخط من الجزء الأول في الفقرة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

يضبط الإزاحات غير الصفرية الافتراضية للهوامش الفعلية للفقرة (Indent وMarginLeft) عندما تكون العلامات مفعَّلة (كما يفعل PowerPoint عند تمكين العلامات/الترقيم). إذا عُطّلت العلامات يتم مجرد إعادة تعيين Indent وMarginLeft (كما يفعل PowerPoint عند تعطيل العلامات/الترقيم). تُطبَّق إزاحات الهوامش بالنسبة إلى سياق العلامة الحالي – IBulletFormat.Type و.NumberedBulletStyle وFontHeight للجزء الأول. تُطبَّق الإزاحات غير الصفرية على Indent وMarginLeft الفاعلين للفقرة الحالية (لتصبح القيم محلية).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق العلامة الفعلية مع تطبيق الوراثة.

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