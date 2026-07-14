---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: خواص قالب‌بندی گلولهٔ پاراگراف را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

خواص قالب‌بندی گلولهٔ پاراگراف را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | نوع گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [setType(byte value)](#setType-byte-) | نوع گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [getChar()](#getChar--) | کاراکتر گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [setChar(char value)](#setChar-char-) | کاراکتر گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [getFont()](#getFont--) | قلم گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | قلم گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [getHeight()](#getHeight--) | ارتفاع گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [setHeight(float value)](#setHeight-float-) | ارتفاع گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [getColor()](#getColor--) | قالب رنگی گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند. |
| [getPicture()](#getPicture--) | تصویری که به عنوان گلوله در پاراگراف استفاده می‌شود را بدون وراثت بر می‌گرداند. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | اولین عدد مورد استفاده برای گروه گلوله‌های شماره‌دار را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | اولین عدد مورد استفاده برای گروه گلوله‌های شماره‌دار را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | سبک گلولهٔ شماره‌دار را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | سبک گلولهٔ شماره‌دار را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. |
| [isBulletHardColor()](#isBulletHardColor--) | تعیین می‌کند آیا گلوله رنگ خاص خود را دارد یا رنگ را از اولین بخش در پاراگراف به ارث می‌برد. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | تعیین می‌کند آیا گلوله رنگ خاص خود را دارد یا رنگ را از اولین بخش در پاراگراف به ارث می‌برد. |
| [isBulletHardFont()](#isBulletHardFont--) | تعیین می‌کند آیا گلوله قلم خاص خود را دارد یا قلم را از اولین بخش در پاراگراف به ارث می‌برد. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | تعیین می‌کند آیا گلوله قلم خاص خود را دارد یا قلم را از اولین بخش در پاراگراف به ارث می‌برد. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | شیفت‌های غیر صفر پیش‌فرض برای تورفتگی (Indent) و حاشیه چپ (MarginLeft) مؤثر پاراگراف را هنگام فعال بودن گلوله‌ها تنظیم می‌کند (مانند PowerPoint هنگام فعال‌سازی گلوله/شماره‌گذاری). |
| [getEffective()](#getEffective--) | داده‌های مؤثر قالب‌بندی گلوله را با اعمال وراثت دریافت می‌کند. |
### getType() {#getType--}
```
public abstract byte getType()
```

نوع گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [BulletType](../../com.aspose.slides/bullettype).

**بازگشت:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

نوع گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [BulletType](../../com.aspose.slides/bullettype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

کاراکتر گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن char.

**بازگشت:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

کاراکتر گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن char.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

قلم گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

قلم گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

ارتفاع گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. مقدار Float.NaN تعیین می‌کند که گلوله ارتفاع را از اولین بخش در پاراگراف به ارث می‌برد. قابل خواندن/نوشتن float.

**بازگشت:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

ارتفاع گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. مقدار Float.NaN تعیین می‌کند که گلوله ارتفاع را از اولین بخش در پاراگراف به ارث می‌برد. قابل خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

قالب رنگی گلولهٔ پاراگراف را بدون وراثت بر می‌گرداند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

تصویر استفاده‌شده به عنوان گلوله در پاراگراف را بدون وراثت بر می‌گرداند. فقط خواندنی [ISlidesPicture](../../com.aspose.slides/islidespicture).

**بازگشت:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

اولین عدد مورد استفاده برای گروه گلوله‌های شماره‌دار را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن short.

**بازگشت:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

اولین عدد مورد استفاده برای گروه گلوله‌های شماره‌دار را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن short.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

سبک گلولهٔ شماره‌دار را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**بازگشت:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

سبک گلولهٔ شماره‌دار را بدون وراثت بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

تعیین می‌کند آیا گلوله رنگ خاص خود را دارد یا رنگ را از اولین بخش در پاراگراف به ارث می‌برد. **NullableBool#True** اگر گلوله رنگ خاص خود را داشته باشد و **NullableBool#False** اگر رنگ را از اولین بخش در پاراگراف به ارث ببرد. قابل خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

تعیین می‌کند آیا گلوله رنگ خاص خود را دارد یا رنگ را از اولین بخش در پاراگراف به ارث می‌برد. **NullableBool#True** اگر گلوله رنگ خاص خود را داشته باشد و **NullableBool#False** اگر رنگ را از اولین بخش در پاراگراف به ارث ببرد. قابل خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

تعیین می‌کند آیا گلوله قلم خاص خود را دارد یا قلم را از اولین بخش در پاراگراف به ارث می‌برد. **NullableBool#True** اگر گلوله قلم خاص خود را داشته باشد و **NullableBool#False** اگر قلم را از اولین بخش در پاراگراف به ارث ببرد. قابل خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

تعیین می‌کند آیا گلوله قلم خاص خود را دارد یا قلم را از اولین بخش در پاراگراف به ارث می‌برد. **NullableBool#True** اگر گلوله قلم خاص خود را داشته باشد و **NullableBool#False** اگر قلم را از اولین بخش در پاراگراف به ارث ببرد. قابل خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

شیفت‌های غیر صفر پیش‌فرض برای تورفتگی و حاشیهٔ چپ مؤثر پاراگراف را هنگام فعال بودن گلوله‌ها تنظیم می‌کند (مانند PowerPoint هنگام فعال‌سازی گلوله/شماره‌گذاری). اگر گلوله‌ها غیرفعال باشند فقط تورفتگی و حاشیهٔ چپ پاراگراف بازنشانی می‌شود (مانند PowerPoint هنگام غیرفعال‌سازی). شیفت‌های تورفتگی نسبت به زمینهٔ جاری گلوله – IBulletFormat.Type، .NumberedBulletStyle و FontHeight اولین بخش – اعمال می‌شوند. شیفت‌های غیر صفر به تورفتگی و حاشیهٔ چپ مؤثر پاراگراف جاری اعمال می‌شوند (مقدارهای نتیجه به‌صورت مقادیر محلی هستند). |
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

داده‌های مؤثر قالب‌بندی گلوله را با در نظر گرفتن وراثت دریافت می‌کند.

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

**بازگشت:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - یک [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).