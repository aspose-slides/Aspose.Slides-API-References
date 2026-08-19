---
title: BulletFormat
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر خصوصیات قالب‌بندی گلولهٔ پاراگراف است.
type: docs
url: /fa/com.aspose.slides/bulletformat/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

نمایانگر خصوصیات قالب‌بندی گلولهٔ پاراگراف است.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | نوع گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. |
| [setType(byte value)](#setType-byte-) | نوع گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. |
| [getChar()](#getChar--) | کاراکتر گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. |
| [setChar(char value)](#setChar-char-) | کاراکتر گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. |
| [getFont()](#getFont--) | قلم گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | قلم گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. |
| [getHeight()](#getHeight--) | ارتفاع گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. |
| [setHeight(float value)](#setHeight-float-) | ارتفاع گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. |
| [getColor()](#getColor--) | قالب رنگی گرولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | عدد اولی که برای گروهی از گلوله‌های شماره‌دار استفاده می‌شود را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | عدد اولی که برای گروهی از گلوله‌های شماره‌دار استفاده می‌شود را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | سبک یک گلولهٔ شماره‌دار را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | سبک یک گلولهٔ شماره‌دار را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. |
| [isBulletHardColor()](#isBulletHardColor--) | تعیین می‌کند آیا گلوله رنگ خود را دارد یا از اولین بخش در پاراگراف به ارث می‌برد. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | تعیین می‌کند آیا گلوله رنگ خود را دارد یا از اولین بخش در پاراگراف به ارث می‌برد. |
| [isBulletHardFont()](#isBulletHardFont--) | تعیین می‌کند آیا گلوله قلم خود را دارد یا از اولین بخش در پاراگراف به ارث می‌برد. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | تعیین می‌کند آیا گلوله قلم خود را دارد یا از اولین بخش در پاراگراف به ارث می‌برد. |
| [getPicture()](#getPicture--) | تصویری که به عنوان گلوله در یک پاراگراف بدون وراثت استفاده می‌شود را برمی‌گرداند. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | جابجایی‌های غیر صفر پیش‌فرض را برای تورفتگی مؤثر پاراگراف (Indent) و حاشیه چپ (MarginLeft) تنظیم می‌کند وقتی گلوله‌ها فعال هستند (مانند PowerPoint که هنگام فعال‌سازی گلوله‌ها/شماره‌گذاری پاراگراف این کار را می‌کند). |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر گلوله را با اعمال وراثت دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```

نوع گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [BulletType](../../com.aspose.slides/bullettype).

**بازگشت:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

نوع گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [BulletType](../../com.aspose.slides/bullettype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public final char getChar()
```

کاراکتر گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن  char .

**بازگشت:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

کاراکتر گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن  char .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public final IFontData getFont()
```

قلم گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

قلم گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

ارتفاع گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. مقدار Float.NaN تعیین می‌کند که گلوله ارتفاع را از اولین بخش در پاراگراف به ارث می‌برد. قابل‌خواندن/قابل‌نوشتن  float .

--------------------

یک مقدار ارتفاع منفی به این معنی است که ارتفاع بر حسب پوینت داده شده و مقدار مثبت به این معنی است که ارتفاع درصدی از متن اطراف است.

**بازگشت:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

ارتفاع گلولهٔ یک پاراگراف بدون وراثت را برمی‌گرداند یا تنظیم می‌کند. مقدار Float.NaN تعیین می‌کند که گلوله ارتفاع را از اولین بخش در پاراگراف به ارث می‌برد. قابل‌خواندن/قابل‌نوشتن  float .

--------------------

یک مقدار ارتفاع منفی به این معنی است که ارتفاع بر حسب پوینت داده شده و مقدار مثبت به این معنی است که ارتفاع درصدی از متن اطراف است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

قالب رنگی یک گلوله در یک پاراگراف بدون وراثت را برمی‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

عدد اولی که برای گروهی از گلوله‌های شماره‌دار استفاده می‌شود را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن  short .

**بازگشت:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

عدد اولی که برای گروهی از گلوله‌های شماره‌دار استفاده می‌شود را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن  short .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

سبک یک گلولهٔ شماره‌دار را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**بازگشت:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

سبک یک گلولهٔ شماره‌دار را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

تعیین می‌کند آیا گلوله رنگ خود را دارد یا از اولین بخش در پاراگراف به ارث می‌برد. **NullableBool.True** اگر گلوله رنگ خود را داشته باشد و **NullableBool.False** اگر رنگ را از اولین بخش در پاراگراف به ارث ببرد. قابل‌خواندن/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

تعیین می‌کند آیا گلوله رنگ خود را دارد یا از اولین بخش در پاراگراف به ارث می‌برد. **NullableBool.True** اگر گلوله رنگ خود را داشته باشد و **NullableBool.False** اگر رنگ را از اولین بخش در پاراگراف به ارث ببرد. قابل‌خواندن/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

تعیین می‌کند آیا گلوله قلم خود را دارد یا از اولین بخش در پاراگراف به ارث می‌برد. **NullableBool.True** اگر گلوله قلم خود را داشته باشد و **NullableBool.False** اگر قلم را از اولین بخش در پاراگراف به ارث ببرد. قابل‌خواندن/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

تعیین می‌کند آیا گلوله قلم خود را دارد یا از اولین بخش در پاراگراف به ارث می‌برد. **NullableBool.True** اگر گلوله قلم خود را داشته باشد و **NullableBool.False** اگر قلم را از اولین بخش در پاراگراف به ارث ببرد. قابل‌خواندن/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

تصویر استفاده‌شده به عنوان گلوله در یک پاراگراف بدون وراثت را برمی‌گرداند. فقط‌خواندنی [ISlidesPicture](../../com.aspose.slides/islidespicture).

**بازگشت:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

جابجایی‌های غیر صفر پیش‌فرض را برای تورفتگی مؤثر پاراگراف (Indent) و حاشیه چپ (MarginLeft) تنظیم می‌کند وقتی گلوله‌ها فعال هستند (مانند PowerPoint که هنگام فعال‌سازی گلوله‌ها/شماره‌گذاری پاراگراف این کار را می‌کند). اگر گلوله‌ها غیرفعال باشند فقط تورفتگی پاراگراف (Indent) و حاشیه چپ (MarginLeft) بازنشانی می‌شوند (مانند PowerPoint که هنگام غیرفعال‌سازی گلوله‌ها/شماره‌گذاری پاراگراف این کار را می‌کند). جابجایی‌های تورفتگی نسبت به زمینهٔ فعلی گلوله – IBulletFormat.Type، .NumberedBulletStyle و FontHeight اولین بخش – اعمال می‌شوند. جابجایی‌های غیر صفر به تورفتگی مؤثر (Indent) و حاشیه چپ (MarginLeft) پاراگراف جاری اعمال می‌شوند (مقادیری محلی می‌شوند).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی مؤثر گلوله را با اعمال وراثت دریافت می‌کند.

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
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط‌خواندنی long.

**بازگشت:**
long