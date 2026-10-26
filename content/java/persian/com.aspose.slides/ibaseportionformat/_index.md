---
title: IBasePortionFormat
second_title: Aspose.Slides برای Java مرجع API
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است.
type: docs
url: /fa/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. بر خلاف [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، همهٔ ویژگی‌های این کلاس قابل نوشتن هستند.

--------------------

این کلاس برای بازگردانی و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف‌شده برای بخش خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر هیچ وراثتی اعمال نمی‌شود، بنابراین در اکثر موارد مقادیر «نامشخص» دریافت می‌کنید.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل وارثتی، باید از متد [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) استفاده کنید که یک نمونهٔ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) را بازمی‌گرداند.
## متدها

| متد | توضیح |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | ویژگی‌های LineFormat را برای حاشیه‌گذاری متن بازمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | ویژگی‌های FillFormat متن را بازمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | ویژگی‌های EffectFormat متن را بازمی‌گرداند. |
| [getHighlightColor()](#getHighlightColor--) | رنگی را که برای برجسته‌سازی متن استفاده می‌شود بازمی‌گرداند. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | ویژگی‌های LineFormat را که برای حاشیه‌گذاری خط زیرخط استفاده می‌شود بازمی‌گرداند. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | ویژگی‌های FillFormat خط زیرخط را بازمی‌گرداند. |
| [getFontBold()](#getFontBold--) | تعیین می‌کند که آیا قلم توپر است یا خیر. |
| [setFontBold(byte value)](#setFontBold-byte-) | تعیین می‌کند که آیا قلم توپر است یا خیر. |
| [getFontItalic()](#getFontItalic--) | تعیین می‌کند که آیا قلم ایتالیک است یا خیر. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | تعیین می‌کند که آیا قلم ایتالیک است یا خیر. |
| [getKumimoji()](#getKumimoji--) | تعیین می‌کند که آیا اعداد باید چینش متن عمودی مخصوص زبان‌های شرقی را نادیده بگیرند یا خیر. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | تعیین می‌کند که آیا اعداد باید چینش متن عمودی مخصوص زبان‌های شرقی را نادیده بگیرند یا خیر. |
| [getNormaliseHeight()](#getNormaliseHeight--) | تعیین می‌کند که آیا ارتفاع متن باید نرمال شود یا خیر. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | تعیین می‌کند که آیا ارتفاع متن باید نرمال شود یا خیر. |
| [getProofDisabled()](#getProofDisabled--) | تعیین می‌کند که آیا متن نباید بررسی شود یا خیر. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | تعیین می‌کند که آیا متن نباید بررسی شود یا خیر. |
| [getFontUnderline()](#getFontUnderline--) | نوع زیرخط متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | نوع زیرخط متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [getTextCapType()](#getTextCapType--) | نوع بزرگ‌نویسی متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | نوع بزرگ‌نویسی متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [getStrikethroughType()](#getStrikethroughType--) | نوع خط‌خوردهٔ متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | نوع خط‌خوردهٔ متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خودش است یا از ویژگی‌های LineFormat متن وراثت می‌گیرد. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خودش است یا از ویژگی‌های LineFormat متن وراثت می‌گیرد. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خودش است یا از ویژگی‌های FillFormat متن وراثت می‌گیرد. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خودش است یا از ویژگی‌های FillFormat متن وراثت می‌گیرد. |
| [getFontHeight()](#getFontHeight--) | ارتفاع قلم یک بخش را بازمی‌گرداند یا تنظیم می‌کند. |
| [setFontHeight(float value)](#setFontHeight-float-) | ارتفاع قلم یک بخش را بازمی‌گرداند یا تنظیم می‌کند. |
| [getLatinFont()](#getLatinFont--) | اطلاعات قلم لاتین را بازمی‌گرداند یا تنظیم می‌کند. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | اطلاعات قلم لاتین را بازمی‌گرداند یا تنظیم می‌کند. |
| [getEastAsianFont()](#getEastAsianFont--) | اطلاعات قلم آسیای شرقی را بازمی‌گرداند یا تنظیم می‌کند. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | اطلاعات قلم آسیای شرقی را بازمی‌گرداند یا تنظیم می‌کند. |
| [getComplexScriptFont()](#getComplexScriptFont--) | اطلاعات قلم اسکریپت پیچیده را بازمی‌گرداند یا تنظیم می‌کند. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | اطلاعات قلم اسکریپت پیچیده را بازمی‌گرداند یا تنظیم می‌کند. |
| [getSymbolFont()](#getSymbolFont--) | اطلاعات قلم نمادین را بازمی‌گرداند یا تنظیم می‌کند. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | اطلاعات قلم نمادین را بازمی‌گرداند یا تنظیم می‌کند. |
| [getEscapement()](#getEscapement--) | متن بالا یا پایین‌نویس را بازمی‌گرداند یا تنظیم می‌کند. |
| [setEscapement(float value)](#setEscapement-float-) | متن بالا یا پایین‌نویس را بازمی‌گرداند یا تنظیم می‌کند. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود، بازمی‌گرداند یا تنظیم می‌کند. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود، بازمی‌گرداند یا تنظیم می‌کند. |
| [getLanguageId()](#getLanguageId--) | شناسهٔ یک زبان اثبات‌گر را بازمی‌گرداند یا تنظیم می‌کند. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | شناسهٔ یک زبان اثبات‌گر را بازمی‌گرداند یا تنظیم می‌کند. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | شناسهٔ یک زبان جایگزین را بازمی‌گرداند یا تنظیم می‌کند. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | شناسهٔ یک زبان جایگزین را بازمی‌گرداند یا تنظیم می‌کند. |
| [getSpacing()](#getSpacing--) | افزایش فاصلهٔ بین کاراکترها را بازمی‌گرداند یا تنظیم می‌کند. |
| [setSpacing(float value)](#setSpacing-float-) | افزایش فاصلهٔ بین کاراکترها را بازمی‌گرداند یا تنظیم می‌کند. |
| [getSpellCheck()](#getSpellCheck--) | مقداری را که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر، دریافت یا تنظیم می‌کند. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | مقداری را که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر، دریافت یا تنظیم می‌کند. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

ویژگی‌های LineFormat را برای حاشیه‌گذاری متن بازمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازمی‌گرداند:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

ویژگی‌های FillFormat متن را بازمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازمی‌گرداند:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

ویژگی‌های EffectFormat متن را بازمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**بازمی‌گرداند:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

رنگی را که برای برجسته‌سازی متن استفاده می‌شود بازمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازمی‌گرداند:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

ویژگی‌های LineFormat را که برای حاشیه‌گذاری خط زیرخط استفاده می‌شود بازمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازمی‌گرداند:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

ویژگی‌های FillFormat خط زیرخط را بازمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازمی‌گرداند:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

تعیین می‌کند که آیا قلم توپر است یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

تعیین می‌کند که آیا قلم توپر است یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

تعیین می‌کند که آیا قلم ایتالیک است یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

تعیین می‌کند که آیا قلم ایتالیک است یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

تعیین می‌کند که آیا اعداد باید چینش متن عمودی مخصوص زبان‌های شرقی را نادیده بگیرند یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

تعیین می‌کند که آیا اعداد باید چینش متن عمودی مخصوص زبان‌های شرقی را نادیده بگیرند یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

تعیین می‌کند که آیا ارتفاع متن باید نرمال شود یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

تعیین می‌کند که آیا ارتفاع متن باید نرمال شود یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

تعیین می‌کند که آیا متن نباید بررسی شود یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

تعیین می‌کند که آیا متن نباید بررسی شود یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

نوع زیرخط متن را بازمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**بازمی‌گرداند:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

نوع زیرخط متن را بازمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

نوع بزرگ‌نویسی متن را بازمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [TextCapType](../../com.aspose.slides/textcaptype).

**بازمی‌گرداند:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

نوع بزرگ‌نویسی متن را بازمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [TextCapType](../../com.aspose.slides/textcaptype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

نوع خط‌خوردهٔ متن را بازمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**بازمی‌گرداند:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

نوع خط‌خوردهٔ متن را بازمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خودش است یا از ویژگی‌های LineFormat متن وراثت می‌گیرد. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خودش است یا از ویژگی‌های LineFormat متن وراثت می‌گیرد. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خودش است یا از ویژگی‌های FillFormat متن وراثت می‌گیرد. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خودش است یا از ویژگی‌های FillFormat متن وراثت می‌گیرد. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

ارتفاع قلم یک بخش را بازمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی float.

**بازمی‌گرداند:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

ارتفاع قلم یک بخش را بازمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

اطلاعات قلم لاتین را بازمی‌گرداند یا تنظیم می‌کند. Null به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

اطلاعات قلم لاتین را بازمی‌گرداند یا تنظیم می‌کند. Null به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

اطلاعات قلم آسیای شرقی را بازمی‌گرداند یا تنظیم می‌کند. Null به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

اطلاعات قلم آسیای شرقی را بازمی‌گرداند یا تنظیم می‌کند. Null به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

اطلاعات قلم اسکریپت پیچیده را بازمی‌گرداند یا تنظیم می‌کند. Null به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

اطلاعات قلم اسکریپت پیچیده را بازمی‌گرداند یا تنظیم می‌کند. Null به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

اطلاعات قلم نمادین را بازمی‌گرداند یا تنظیم می‌کند. Null به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

اطلاعات قلم نمادین را بازمی‌گرداند یا تنظیم می‌کند. Null به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

متن بالا یا پایین‌نویس را بازمی‌گرداند یا تنظیم می‌کند. مقدار از -100% (پایین‌نویس) تا 100% (بالا‌نویس). **Float.NaN** به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی float.

**بازمی‌گرداند:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

متن بالا یا پایین‌نویس را بازمی‌گرداند یا تنظیم می‌کند. مقدار از -100% (پایین‌نویس) تا 100% (بالا‌نویس). **Float.NaN** به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود، بازمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی float.

**بازمی‌گرداند:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود، بازمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

شناسهٔ یک زبان اثبات‌گر را بازمی‌گرداند یا تنظیم می‌کند. برای بررسی املاء و گرامر استفاده می‌شود. خواندنی/نوشتنی String.

**بازمی‌گرداند:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

شناسهٔ یک زبان اثبات‌گر را بازمی‌گرداند یا تنظیم می‌کند. برای بررسی املاء و گرامر استفاده می‌شود. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

شناسهٔ یک زبان جایگزین را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازمی‌گرداند:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

شناسهٔ یک زبان جایگزین را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

افزایش فاصلهٔ بین کاراکترها را بازمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی float.

**بازمی‌گرداند:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

افزایش فاصلهٔ بین کاراکترها را بازمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنی undefined است و باید از Master به ارث برده شود. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

مقداری را که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر، دریافت یا تنظیم می‌کند. وقتی این ویژگی روی false تنظیم شود، بررسی املایی برای عناصر متن سرکوب می‌شود. وقتی روی true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض false است.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // دسترسی به اولین بخش متن داخل اولین شکل در اولین اسلاید
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // فعال سازی بررسی املایی برای این بخش متن
>      portion.getPortionFormat().setSpellCheck(true);
>      // ذخیره ارائه تغییر یافته
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گرداند:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

مقداری را که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر، دریافت یا تنظیم می‌کند. وقتی این ویژگی روی false تنظیم شود، بررسی املایی برای عناصر متن سرکوب می‌شود. وقتی روی true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض false است.

--------------------

> ```
public abstract void setSpellCheck(boolean value)
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |