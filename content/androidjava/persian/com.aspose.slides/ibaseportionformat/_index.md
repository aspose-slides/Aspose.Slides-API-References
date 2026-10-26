---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the text portion formatting properties.
type: docs
url: /fa/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

--------------------

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف شده برای بخش خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر، هیچ ارث‌بری اعمال نمی‌شود، بنابراین در بیشتر موارد مقادیری دریافت می‌کنید که به معنای «نامشخص» هستند.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌بری، لازم است از روش [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) استفاده کنید که یک نمونه [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) را برمی‌گرداند.
## متدها

| متد | توضیح |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | ویژگی‌های LineFormat برای حاشیه‌گذاری متن را برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | ویژگی‌های FillFormat متن را برمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | ویژگی‌های EffectFormat متن را برمی‌گرداند. |
| [getHighlightColor()](#getHighlightColor--) | رنگ استفاده شده برای برجسته‌کردن متن را برمی‌گرداند. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | ویژگی‌های LineFormat استفاده شده برای حاشیه‌گذاری خط زیرخط را برمی‌گرداند. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. |
| [getFontBold()](#getFontBold--) | تعیین می‌کند که قلم بولد است یا خیر. |
| [setFontBold(byte value)](#setFontBold-byte-) | تعیین می‌کند که قلم بولد است یا خیر. |
| [getFontItalic()](#getFontItalic--) | تعیین می‌کند که قلم ایتالیک است یا خیر. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | تعیین می‌کند که قلم ایتالیک است یا خیر. |
| [getKumimoji()](#getKumimoji--) | تعیین می‌کند که اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | تعیین می‌کند که اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند. |
| [getNormaliseHeight()](#getNormaliseHeight--) | تعیین می‌کند که ارتفاع متن باید نرمال‌سازی شود. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | تعیین می‌کند که ارتفاع متن باید نرمال‌سازی شود. |
| [getProofDisabled()](#getProofDisabled--) | تعیین می‌کند که متن نباید بررسی املایی شود. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | تعیین می‌کند که متن نباید بررسی املایی شود. |
| [getFontUnderline()](#getFontUnderline--) | بازگرداندن یا تنظیم نوع زیرخط متن. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | بازگرداندن یا تنظیم نوع زیرخط متن. |
| [getTextCapType()](#getTextCapType--) | بازگرداندن یا تنظیم نوع حروف بزرگ/کوچک متن. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | بازگرداندن یا تنظیم نوع حروف بزرگ/کوچک متن. |
| [getStrikethroughType()](#getStrikethroughType--) | بازگرداندن یا تنظیم نوع خط خورده متن. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | بازگرداندن یا تنظیم نوع خط خورده متن. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | تعیین می‌کند که سبک زیرخط دارای ویژگی‌های LineFormat خود است یا آن را از ویژگی‌های LineFormat متن ارث می‌برد. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | تعیین می‌کند که سبک زیرخط دارای ویژگی‌های LineFormat خود است یا آن را از ویژگی‌های LineFormat متن ارث می‌برد. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | تعیین می‌کند که سبک زیرخط دارای ویژگی‌های FillFormat خود است یا آن را از ویژگی‌های FillFormat متن ارث می‌برد. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | تعیین می‌کند که سبک زیرخط دارای ویژگی‌های FillFormat خود است یا آن را از ویژگی‌های FillFormat متن ارث می‌برد. |
| [getFontHeight()](#getFontHeight--) | بازگرداندن یا تنظیم ارتفاع قلم یک بخش. |
| [setFontHeight(float value)](#setFontHeight-float-) | بازگرداندن یا تنظیم ارتفاع قلم یک بخش. |
| [getLatinFont()](#getLatinFont--) | بازگرداندن یا تنظیم اطلاعات قلم لاتین. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | بازگرداندن یا تنظیم اطلاعات قلم لاتین. |
| [getEastAsianFont()](#getEastAsianFont--) | بازگرداندن یا تنظیم اطلاعات قلم شرق آسیایی. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | بازگرداندن یا تنظیم اطلاعات قلم شرق آسیایی. |
| [getComplexScriptFont()](#getComplexScriptFont--) | بازگرداندن یا تنظیم اطلاعات قلم اسکریپت پیچیده. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | بازگرداندن یا تنظیم اطلاعات قلم اسکریپت پیچیده. |
| [getSymbolFont()](#getSymbolFont--) | بازگرداندن یا تنظیم اطلاعات قلم نمادین. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | بازگرداندن یا تنظیم اطلاعات قلم نمادین. |
| [getEscapement()](#getEscapement--) | بازگرداندن یا تنظیم متن بالانویس یا زیرنویس. |
| [setEscapement(float value)](#setEscapement-float-) | بازگرداندن یا تنظیم متن بالانویس یا زیرنویس. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | بازگرداندن یا تنظیم حداقل سایز قلم که برای آن کرنینگ فعال شود. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | بازگرداندن یا تنظیم حداقل سایز قلم که برای آن کرنینگ فعال شود. |
| [getLanguageId()](#getLanguageId--) | بازگرداندن یا تنظیم شناسه یک زبان تصحیح. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | بازگرداندن یا تنظیم شناسه یک زبان تصحیح. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | بازگرداندن یا تنظیم شناسه یک زبان جایگزین. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | بازگرداندن یا تنظیم شناسه یک زبان جایگزین. |
| [getSpacing()](#getSpacing--) | بازگرداندن یا تنظیم افزایش فاصله بین حروف. |
| [setSpacing(float value)](#setSpacing-float-) | بازگرداندن یا تنظیم افزایش فاصله بین حروف. |
| [getSpellCheck()](#getSpellCheck--) | دریافت یا تنظیم مقداری که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | دریافت یا تنظیم مقداری که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

ویژگی‌های LineFormat برای حاشیه‌گذاری متن را بازمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

ویژگی‌های FillFormat متن را بازمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

ویژگی‌های EffectFormat متن را بازمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**بازگشت:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

رنگ استفاده شده برای برجسته‌کردن متن را بازمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

ویژگی‌های LineFormat استفاده شده برای حاشیه‌گذاری خط زیرخط را بازمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

ویژگی‌های FillFormat خط زیرخط را بازمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

تعیین می‌کند که قلم بولد است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

تعیین می‌کند که قلم بولد است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

تعیین می‌کند که قلم ایتالیک است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

تعیین می‌کند که قلم ایتالیک است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

تعیین می‌کند که اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

تعیین می‌کند که اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

تعیین می‌کند که ارتفاع متن باید نرمال‌سازی شود. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

تعیین می‌کند که ارتفاع متن باید نرمال‌سازی شود. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

تعیین می‌کند که متن نباید بررسی املایی شود. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

تعیین می‌کند که متن نباید بررسی املایی شود. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

بازگرداندن یا تنظیم نوع زیرخط متن. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**بازگشت:**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

بازگرداندن یا تنظیم نوع زیرخط متن. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

بازگرداندن یا تنظیم نوع حروف بزرگ/کوچک متن. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [TextCapType](../../com.aspose.slides/textcaptype).

**بازگشت:**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

بازگرداندن یا تنظیم نوع حروف بزرگ/کوچک متن. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [TextCapType](../../com.aspose.slides/textcaptype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

بازگرداندن یا تنظیم نوع خط خورده متن. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**بازگشت:**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

بازگرداندن یا تنظیم نوع خط خورده متن. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

تعیین می‌کند که سبک زیرخط دارای ویژگی‌های LineFormat خود است یا آن را از ویژگی‌های LineFormat متن ارث می‌برد. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

تعیین می‌کند که سبک زیرخط دارای ویژگی‌های LineFormat خود است یا آن را از ویژگی‌های LineFormat متن ارث می‌برد. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

تعیین می‌کند که سبک زیرخط دارای ویژگی‌های FillFormat خود است یا آن را از ویژگی‌های FillFormat متن ارث می‌برد. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

تعیین می‌کند که سبک زیرخط دارای ویژگی‌های FillFormat خود است یا آن را از ویژگی‌های FillFormat متن ارث می‌برد. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

بازگرداندن یا تنظیم ارتفاع قلم یک بخش. **Float.NaN** به معنای نامشخص بودن ارتفاع است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی float.

**بازگشت:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

بازگرداندن یا تنظیم ارتفاع قلم یک بخش. **Float.NaN** به معنای نامشخص بودن ارتفاع است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

بازگرداندن یا تنظیم اطلاعات قلم لاتین. مقدار Null به معنای نامشخص بودن قلم است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

بازگرداندن یا تنظیم اطلاعات قلم لاتین. مقدار Null به معنای نامشخص بودن قلم است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

بازگرداندن یا تنظیم اطلاعات قلم شرق آسیایی. مقدار Null به معنای نامشخص بودن قلم است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

بازگرداندن یا تنظیم اطلاعات قلم شرق آسیایی. مقدار Null به معنای نامشخص بودن قلم است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

بازگرداندن یا تنظیم اطلاعات قلم اسکریپت پیچیده. مقدار Null به معنای نامشخص بودن قلم است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

بازگرداندن یا تنظیم اطلاعات قلم اسکریپت پیچیده. مقدار Null به معنای نامشخص بودن قلم است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

بازگرداندن یا تنظیم اطلاعات قلم نمادین. مقدار Null به معنای نامشخص بودن قلم است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

بازگرداندن یا تنظیم اطلاعات قلم نمادین. مقدار Null به معنای نامشخص بودن قلم است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

بازگرداندن یا تنظیم متن بالانویس یا زیرنویس. مقدار از -100% (زیرنویس) تا 100% (بالانویس). **Float.NaN** به معنای نامشخص بودن مقدار است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی float.

**بازگشت:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

بازگرداندن یا تنظیم متن بالانویس یا زیرنویس. مقدار از -100% (زیرنویس) تا 100% (بالانویس). **Float.NaN** به معنای نامشخص بودن مقدار است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

بازگرداندن یا تنظیم حداقل سایز قلم که برای آن کرنینگ فعال شود. **Float.NaN** به معنای نامشخص بودن مقدار است و باید از مستר ارث‌برده شود. خواندنی/نوشتنی float.

**بازگشت:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

بازگرداندن یا تنظیم حداقل سایز قلم که برای آن کرنینگ فعال شود. **Float.NaN** به معنای نامشخص بودن مقدار است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

بازگرداندن یا تنظیم شناسه یک زبان تصحیح. برای بررسی املایی و گرامری استفاده می‌شود. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

بازگرداندن یا تنظیم شناسه یک زبان تصحیح. برای بررسی املایی و گرامری استفاده می‌شود. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

بازگرداندن یا تنظیم شناسه یک زبان جایگزین. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

بازگرداندن یا تنظیم شناسه یک زبان جایگزین. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

بازگرداندن یا تنظیم افزایش فاصله بین حروف. **Float.NaN** به معنای نامشخص بودن مقدار است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی float.

**بازگشت:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

بازگرداندن یا تنظیم افزایش فاصله بین حروف. **Float.NaN** به معنای نامشخص بودن مقدار است و باید از مستر ارث‌برده شود. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

دریافت یا تنظیم مقداری که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی املایی برای عناصر متنی غیرفعال می‌شود. وقتی به true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض false است.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // دسترسی به اولین بخش متن داخل اولین شکل در اولین اسلاید
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // فعال‌سازی بررسی املایی برای این بخش متن
>      portion.getPortionFormat().setSpellCheck(true);
>      // ذخیره‌سازی ارائه تغییر یافته
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

دریافت یا تنظیم مقداری که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی املای برای عناصر متنی غیرفعال می‌شود. وقتی به true تنظیم شود، بررسی املا مجاز است. مقدار پیش‌فرض false است.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // دسترسی به اولین بخش متن داخل اولین شکل در اولین اسلاید
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // فعال‌سازی بررسی املایی برای این بخش متن
>      portion.getPortionFormat().setSpellCheck(true);
>      // ذخیره‌سازی ارائه تغییر یافته
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |