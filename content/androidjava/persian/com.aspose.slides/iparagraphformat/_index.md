---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
url: /fa/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است. بر خلاف [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

--------------------

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده برای پاراگراف خاص استفاده می‌شود. این به این معناست که هنگام دریافت مقادیر هیچ وراثتی اعمال نمی‌شود، بنابراین در اکثر موارد مقادیری که «undefined» معنی می‌شوند، دریافت خواهید کرد.

برای دریافت مقادیر پارامترهای قالب‌بندی مؤثر شامل ارث‌بری، باید از متد [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) استفاده کنید که یک نمونهٔ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) را برمی‌گرداند.
## متدها

| متد | توضیح |
| --- | --- |
| [getBullet()](#getBullet--) | قالب گلوله پاراگراف را باز می‌گرداند. |
| [getDepth()](#getDepth--) | عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [setDepth(short value)](#setDepth-short-) | عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [getAlignment()](#getAlignment--) | تراز متن در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [setAlignment(int value)](#setAlignment-int-) | تراز متن در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [getSpaceWithin()](#getSpaceWithin--) | مقدار فضای بین خطوط پایه در یک پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | مقدار فضای بین خطوط پایه در یک پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [getSpaceBefore()](#getSpaceBefore--) | مقدار فضای قبل از اولین خط در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | مقدار فضای قبل از اولین خط در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [getSpaceAfter()](#getSpaceAfter--) | مقدار فضای بعد از آخرین خط در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | مقدار فضای بعد از آخرین خط در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | تعیین می‌کند آیا شکست خط آسیای شرقی در یک پاراگراف استفاده می‌شود. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | تعیین می‌کند آیا شکست خط آسیای شرقی در یک پاراگراف استفاده می‌شود. |
| [getRightToLeft()](#getRightToLeft--) | تعیین می‌کند آیا نوشتار راست به چپ در یک پاراگراف استفاده می‌شود. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | تعیین می‌کند آیا نوشتار راست به چپ در یک پاراگراف استفاده می‌شود. |
| [getLatinLineBreak()](#getLatinLineBreak--) | تعیین می‌کند آیا شکست خط لاتین در یک پاراگراف استفاده می‌شود. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | تعیین می‌کند آیا شکست خط لاتین در یک پاراگراف استفاده می‌شود. |
| [getHangingPunctuation()](#getHangingPunctuation--) | تعیین می‌کند آیا نگهداری نقطه‌گذاری معلق در یک پاراگراف استفاده می‌شود. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | تعیین می‌کند آیا نگهداری نقطه‌گذاری معلق در یک پاراگراف استفاده می‌شود. |
| [getMarginLeft()](#getMarginLeft--) | حاشیهٔ چپ در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | حاشیهٔ چپ در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | حاشیهٔ راست در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(float value)](#setMarginRight-float-) | حاشیهٔ راست در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [getIndent()](#getIndent--) | تورفتگی خط اول/تورفتگی معلق پاراگراف را بدون وراثت باز می‌گرداند یا تنظیم می‌کند. |
| [setIndent(float value)](#setIndent-float-) | تورفتگی خط اول/تورفتگی معلق پاراگراف را بدون وراثت باز می‌گرداند یا تنظیم می‌کند. |
| [getDefaultTabSize()](#getDefaultTabSize--) | اندازهٔ پیش‌فرض تب‌بندی را بدون وراثت باز می‌گرداند یا تنظیم می‌کند. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | اندازهٔ پیش‌فرض تب‌بندی را بدون وراثت باز می‌گرداند یا تنظیم می‌کند. |
| [getTabs()](#getTabs--) | تب‌های یک پاراگراف را باز می‌گرداند. |
| [getFontAlignment()](#getFontAlignment--) | تراز فونت در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | تراز فونت در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | قالب پیش‌فرض بخش (portion) یک پاراگراف را باز می‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر پاراگراف را با اعمال وراثت دریافت می‌کند. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

قالب گلوله پاراگراف را باز می‌گرداند. فقط‌خواندنی [IBulletFormat](../../com.aspose.slides/ibulletformat).

**باز می‌گرداند:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار 0 به معنی مقدار نامشخص است. قابل خواندن و نوشتن short.

**باز می‌گرداند:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار 0 به معنی مقدار نامشخص است. قابل خواندن و نوشتن short.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

تراز متن در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [TextAlignment](../../com.aspose.slides/textalignment).

**باز می‌گرداند:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

تراز متن در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [TextAlignment](../../com.aspose.slides/textalignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

مقدار فضای بین خطوط پایه در یک پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت به معنای درصد، مقدار منفی به معنای اندازه به نقطه. وراثتی اعمال نمی‌شود. قابل خواندن و نوشتن float.

**باز می‌گرداند:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

مقدار فضای بین خطوط پایه در یک پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت به معنای درصد، مقدار منفی به معنای اندازه به نقطه. وراثتی اعمال نمی‌شود. قابل خواندن و نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

مقدار فضای قبل از اولین خط در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصدی از اندازهٔ قلم را نشان می‌دهد، مقدار منفی اندازهٔ فضای سفید به نقطه است. قابل خواندن و نوشتن float.

**باز می‌گرداند:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

مقدار فضای قبل از اولین خط در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصدی از اندازهٔ قلم را نشان می‌دهد، مقدار منفی اندازهٔ فضای سفید به نقطه است. قابل خواندن و نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

مقدار فضای بعد از آخرین خط در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصدی از اندازهٔ قلم را نشان می‌دهد، مقدار منفی اندازهٔ فضای سفید به نقطه است. قابل خواندن و نوشتن float.

**باز می‌گرداند:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

مقدار فضای بعد از آخرین خط در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصدی از اندازهٔ قلم را نشان می‌دهد، مقدار منفی اندازهٔ فضای سفید به نقطه است. قابل خواندن و نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

تعیین می‌کند آیا شکست خط آسیای شرقی در یک پاراگراف استفاده می‌شود. وراثتی اعمال نمی‌شود. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**باز می‌گرداند:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

تعیین می‌کند آیا شکست خط آسیای شرقی در یک پاراگراف استفاده می‌شود. وراثتی اعمال نمی‌شود. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

تعیین می‌کند آیا نوشتار راست به چپ در یک پاراگراف استفاده می‌شود. وراثتی اعمال نمی‌شود. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**باز می‌گرداند:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

تعیین می‌کند آیا نوشتار راست به چپ در یک پاراگراف استفاده می‌شود. وراثتی اعمال نمی‌شود. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

تعیین می‌کند آیا شکست خط لاتین در یک پاراگراف استفاده می‌شود. وراثتی اعمال نمی‌شود. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**باز می‌گرداند:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

تعیین می‌کند آیا شکست خط لاتین در یک پاراگراف استفاده می‌شود. وراثتی اعمال نمی‌شود. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

تعیین می‌کند آیا نگهداری نقطه‌گذاری معلق در یک پاراگراف استفاده می‌شود. وراثتی اعمال نمی‌شود. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**باز می‌گرداند:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

تعیین می‌کند آیا نگهداری نقطه‌گذاری معلق در یک پاراگراف استفاده می‌شود. وراثتی اعمال نمی‌شود. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

حاشیهٔ چپ در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن float.

**باز می‌گرداند:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

حاشیهٔ چپ در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

حاشیهٔ راست در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن float.

**باز می‌گرداند:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

حاشیهٔ راست در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

تورفتگی خط اول/تورفتگی معلق پاراگراف را بدون وراثت باز می‌گرداند یا تنظیم می‌کند. تورفتگی معلق می‌تواند با مقادیر منفی تعریف شود. قابل خواندن و نوشتن float.

**باز می‌گرداند:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

تورفتگی خط اول/تورفتگی معلق پاراگراف را بدون وراثت باز می‌گرداند یا تنظیم می‌کند. تورفتگی معلق می‌تواند با مقادیر منفی تعریف شود. قابل خواندن و نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

اندازهٔ پیش‌فرض تب‌بندی را بدون وراثت باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن float.

**باز می‌گرداند:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

اندازهٔ پیش‌فرض تب‌بندی را بدون وراثت باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

تب‌های یک پاراگراف را باز می‌گرداند. فقط‌خواندنی [ITabCollection](../../com.aspose.slides/itabcollection).

**باز می‌گرداند:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

تراز فونت در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [FontAlignment](../../com.aspose.slides/fontalignment).

**باز می‌گرداند:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

تراز فونت در یک پاراگراف بدون وراثت را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [FontAlignment](../../com.aspose.slides/fontalignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

قالب پیش‌فرض بخش (portion) یک پاراگراف را باز می‌گرداند. فقط‌خواندنی [IPortionFormat](../../com.aspose.slides/iportionformat).

**باز می‌گرداند:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی مؤثر پاراگراف را با اعمال وراثت دریافت می‌کند.

**باز می‌گرداند:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).