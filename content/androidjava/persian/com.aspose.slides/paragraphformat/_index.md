---
title: ParagraphFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است.
type: docs
url: /fa/com.aspose.slides/paragraphformat/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است. برخلاف [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

--------------------

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده برای پاراگراف خاص استفاده می‌شود. این به این معناست که هنگام دریافت مقادیر هیچ ارث‌بری اعمال نمی‌شود، بنابراین در اکثر موارد مقادیر «نامتعین» دریافت می‌کنید.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌بری، باید از متد [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) استفاده کنید که یک نمونهٔ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) را برمی‌گرداند.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | یک نمونهٔ جدید از کلاس [ParagraphFormat](../../com.aspose.slides/paragraphformat) را مقداردهی اولیه می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getBullet()](#getBullet--) | قالب گلولهٔ پاراگراف را باز می‌گرداند. |
| [getDepth()](#getDepth--) | عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [setDepth(short value)](#setDepth-short-) | عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [getAlignment()](#getAlignment--) | ترازبندی متن در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [setAlignment(int value)](#setAlignment-int-) | ترازبندی متن در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [getSpaceWithin()](#getSpaceWithin--) | مقدار فضای بین خطوط پایه در پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | مقدار فضای بین خطوط پایه در پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [getSpaceBefore()](#getSpaceBefore--) | مقدار فضای قبل از اولین خط در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | مقدار فضای قبل از اولین خط در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [getSpaceAfter()](#getSpaceAfter--) | مقدار فضای پس از آخرین خط در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | مقدار فضای پس از آخرین خط در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | مشخص می‌کند آیا شکست خط آسیای شرقی در پاراگراف استفاده می‌شود یا خیر. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | مشخص می‌کند آیا شکست خط آسیای شرقی در پاراگراف استفاده می‌شود یا خیر. |
| [getRightToLeft()](#getRightToLeft--) | مشخص می‌کند آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا خیر. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | مشخص می‌کند آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا خیر. |
| [getLatinLineBreak()](#getLatinLineBreak--) | مشخص می‌کند آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا خیر. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | مشخص می‌کند آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا خیر. |
| [getHangingPunctuation()](#getHangingPunctuation--) | مشخص می‌کند آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا خیر. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | مشخص می‌کند آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا خیر. |
| [getMarginLeft()](#getMarginLeft--) | حاشیهٔ چپ در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | حاشیهٔ چپ در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | حاشیهٔ راست در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(float value)](#setMarginRight-float-) | حاشیهٔ راست در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [getIndent()](#getIndent--) | تو رفتگی اولین خط/تو رفتگی معلق پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [setIndent(float value)](#setIndent-float-) | تو رفتگی اولین خط/تو رفتگی معلق پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [getDefaultTabSize()](#getDefaultTabSize--) | اندازهٔ پیش‌فرض تب را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | اندازهٔ پیش‌فرض تب را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [getTabs()](#getTabs--) | تب‌های پاراگراف را باز می‌گرداند. |
| [getFontAlignment()](#getFontAlignment--) | ترازبندی قلم در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | ترازبندی قلم در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | قالب پیش‌فرض بخش پاراگراف را باز می‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های مؤثر قالب‌بندی پاراگراف را با اعمال ارث‌بری دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

یک نمونهٔ جدید از کلاس [ParagraphFormat](../../com.aspose.slides/paragraphformat) را مقداردهی اولیه می‌کند.

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

قالب گلولهٔ پاراگراف را باز می‌گرداند. فقط خواندنی [IBulletFormat](../../com.aspose.slides/ibulletformat).

**باز می‌گرداند:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار 0 به معنای مقدار نامتعین است. خواندن/نوشتن  short .

**باز می‌گرداند:**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار 0 به معنای مقدار نامتعین است. خواندن/نوشتن  short .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

ترازبندی متن در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // یک شیء Presentation ایجاد کنید که نمایانگر یک فایل PPTX است
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // دسترسی به اولین اسلاید
>      ISlide slide = pres.getSlides().get_Item(0);
>      // دسترسی به مکان‌گیر اول و دوم در اسلاید و تبدیل نوع آن به AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // تغییر متن در هر دو مکان‌گیر
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // دریافت اولین پاراگراف مکان‌گیرها
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // ترازبندی پاراگراف متن به مرکز
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Writing نوشتن ارائه به عنوان فایل PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**باز می‌گرداند:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

ترازبندی متن در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // یک شیء Presentation ایجاد کنید که نمایانگر یک فایل PPTX است
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // دسترسی به اولین اسلاید
>      ISlide slide = pres.getSlides().get_Item(0);
>      // دسترسی به مکان‌گیر اول و دوم در اسلاید و تبدیل نوع آن به AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // تغییر متن در هر دو مکان‌گیر
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // دریافت اولین پاراگراف مکان‌گیرها
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // ترازبندی پاراگراف متن به مرکز
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //نوشتن ارائه به عنوان فایل PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

مقدار فضای بین خطوط پایه در پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت به معنی درصد است، مقدار منفی به معنی اندازه به نقطه. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن  float .

**باز می‌گرداند:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

مقدار فضای بین خطوط پایه در پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت به معنی درصد است، مقدار منفی به معنی اندازه به نقطه. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

مقدار فضای قبل از اولین خط در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصد اندازهٔ قلم را مشخص می‌کند، مقدار منفی اندازهٔ فضای سفید را به نقطه مشخص می‌کند. خواندن/نوشتن  float .

**باز می‌گرداند:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

مقدار فضای قبل از اولین خط در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصد اندازهٔ قلم را مشخص می‌کند، مقدار منفی اندازهٔ فضای سفید را به نقطه مشخص می‌کند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

مقدار فضای پس از آخرین خط در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصد اندازهٔ قلم را مشخص می‌کند، مقدار منفی اندازهٔ فضای سفید را به نقطه مشخص می‌کند. خواندن/نوشتن  float .

**باز می‌گرداند:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

مقدار فضای پس از آخرین خط در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصد اندازهٔ قلم را مشخص می‌کند، مقدار منفی اندازهٔ فضای سفید را به نقطه مشخص می‌کند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

مشخص می‌کند آیا شکست خط آسیای شرقی در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**باز می‌گرداند:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

مشخص می‌کند آیا شکست خط آسیای شرقی در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

مشخص می‌کند آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**باز می‌گرداند:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

مشخص می‌کند آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

مشخص می‌کند آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**باز می‌گرداند:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

مشخص می‌کند آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

مشخص می‌کند آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**باز می‌گرداند:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

مشخص می‌کند آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

حاشیهٔ چپ در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**باز می‌گرداند:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

حاشیهٔ چپ در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

حاشیهٔ راست در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**باز می‌گرداند:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

حاشیهٔ راست در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

تو رفتگی اولین خط/تو رفتگی معلق پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. تو رفتگی معلق می‌تواند با مقادیر منفی تعریف شود. خواندن/نوشتن  float .

**باز می‌گرداند:**
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

تو رفتگی اولین خط/تو رفتگی معلق پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. تو رفتگی معلق می‌تواند با مقادیر منفی تعریف شود. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

اندازهٔ پیش‌فرض تب را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**باز می‌گرداند:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

اندازهٔ پیش‌فرض تب را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

تب‌های پاراگراف را باز می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [ITabCollection](../../com.aspose.slides/itabcollection).

**باز می‌گرداند:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

ترازبندی قلم در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [FontAlignment](../../com.aspose.slides/fontalignment).

**باز می‌گرداند:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

ترازبندی قلم در پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [FontAlignment](../../com.aspose.slides/fontalignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

قالب پیش‌فرض بخش پاراگراف را باز می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [IPortionFormat](../../com.aspose.slides/iportionformat).

**باز می‌گرداند:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

داده‌های مؤثر قالب‌بندی پاراگراف را با اعمال ارث‌بری دریافت می‌کند.

--------------------

> ```
> این مثال نشان می‌دهد که برخی از ویژگی‌های مؤثر قالب‌بندی پاراگراف را دریافت می‌کند.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**باز می‌گرداند:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**باز می‌گرداند:**
long