---
title: BasePortionFormat
second_title: مرجع API Aspose.Slides برای جاوا
description: ویژگی‌های قالب‌بندی مشترک بخش متن.
type: docs
url: /fa/com.aspose.slides/baseportionformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

ویژگی‌های قالب‌بندی بخش متن عمومی.
## متدها

| متد | شرح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | خواص LineFormat را برای خط‌کش متن برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | خواص FillFormat متن را برمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | خواص EffectFormat متن را برمی‌گرداند. |
| [getHighlightColor()](#getHighlightColor--) | رنگی را که برای برجسته‌سازی متن استفاده می‌شود، برمی‌گرداند. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | خواص LineFormat مورد استفاده برای خطوط زیرخط را برمی‌گرداند. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | خواص FillFormat خط زیرخط را برمی‌گرداند. |
| [getFontBold()](#getFontBold--) | تعیین می‌کند که آیا قلم توپر است. |
| [setFontBold(byte value)](#setFontBold-byte-) | تعیین می‌کند که آیا قلم توپر است. |
| [getFontItalic()](#getFontItalic--) | تعیین می‌کند که آیا قلم ایتالیک است. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | تعیین می‌کند که آیا قلم ایتالیک است. |
| [getKumimoji()](#getKumimoji--) | تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن مربوط به زبان‌های شرقی را نادیده بگیرند. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن مربوط به زبان‌های شرقی را نادیده بگیرند. |
| [getNormaliseHeight()](#getNormaliseHeight--) | تعیین می‌کند که آیا ارتفاع متن باید نرمال‌سازی شود. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | تعیین می‌کند که آیا ارتفاع متن باید نرمال‌سازی شود. |
| [getProofDisabled()](#getProofDisabled--) | تعیین می‌کند که آیا متن نباید بررسی شود. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | تعیین می‌کند که آیا متن نباید بررسی شود. |
| [getFontUnderline()](#getFontUnderline--) | نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getTextCapType()](#getTextCapType--) | نوع حروف بزرگ متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | نوع حروف بزرگ متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getStrikethroughType()](#getStrikethroughType--) | نوع خط‌خربش متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | نوع خط‌خربش متن را برمی‌گرداند یا تنظیم می‌کند. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن به ارث می‌برد. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن به ارث می‌برد. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن به ارث می‌برد. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن به ارث می‌برد. |
| [getFontHeight()](#getFontHeight--) | ارتفاع قلم یک بخش را برمی‌گرداند یا تنظیم می‌کند. |
| [setFontHeight(float value)](#setFontHeight-float-) | ارتفاع قلم یک بخش را برمی‌گرداند یا تنظیم می‌کند. |
| [getLatinFont()](#getLatinFont--) | اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. |
| [getEastAsianFont()](#getEastAsianFont--) | اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. |
| [getComplexScriptFont()](#getComplexScriptFont--) | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. |
| [getSymbolFont()](#getSymbolFont--) | اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. |
| [getEscapement()](#getEscapement--) | متن صدری یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. |
| [setEscapement(float value)](#setEscapement-float-) | متن صدری یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getLanguageId()](#getLanguageId--) | شناسه زبان بررسی‌گر را برمی‌گرداند یا تنظیم می‌کند. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | شناسه زبان بررسی‌گر را برمی‌گرداند یا تنظیم می‌کند. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | شناسه زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | شناسه زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. |
| [getSpacing()](#getSpacing--) | مقدار افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. |
| [setSpacing(float value)](#setSpacing-float-) | مقدار افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. |
| [getSpellCheck()](#getSpellCheck--) | دریافت یا تنظیم مقداری که نشان می‌دهد آیا غلط‌گیری برای بخش متن فعال است یا نه. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | دریافت یا تنظیم مقداری که نشان می‌دهد آیا غلط‌گیری برای بخش متن فعال است یا نه. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**بازمی‌گرداند:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

خواص LineFormat را برای خط‌کش متن برمی‌گرداند. وراثت اعمال نمی‌شود. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازمی‌گرداند:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

خواص FillFormat متن را برمی‌گرداند. وراثت اعمال نمی‌شود. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازمی‌گرداند:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

خواص EffectFormat متن را برمی‌گرداند. وراثت اعمال نمی‌شود. فقط-خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**بازمی‌گرداند:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

رنگی را که برای برجسته‌سازی متن استفاده می‌شود، برمی‌گرداند. وراثت اعمال نمی‌شود. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازمی‌گرداند:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

خواص LineFormat مورد استفاده برای خطوط زیرخط را برمی‌گرداند. وراثت اعمال نمی‌شود. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازمی‌گرداند:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

خواص FillFormat خط زیرخط را برمی‌گرداند. وراثت اعمال نمی‌شود. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازمی‌گرداند:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

تعیین می‌کند که آیا قلم توپر است. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

تعیین می‌کند که آیا قلم توپر است. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

تعیین می‌کند که آیا قلم ایتالیک است. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

تعیین می‌کند که آیا قلم ایتالیک است. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن مربوط به زبان‌های شرقی را نادیده بگیرند. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن مربوط به زبان‌های شرقی را نادیده بگیرند. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

تعیین می‌کند که آیا ارتفاع متن باید نرمال‌سازی شود. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

تعیین می‌کند که آیا ارتفاع متن باید نرمال‌سازی شود. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

تعیین می‌کند که آیا متن نباید بررسی شود. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

تعیین می‌کند که آیا متن نباید بررسی شود. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**بازمی‌گرداند:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

نوع حروف بزرگ متن را برمی‌گرداند یا تنظیم می‌کند. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [TextCapType](../../com.aspose.slides/textcaptype).

**بازمی‌گرداند:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

نوع حروف بزرگ متن را برمی‌گرداند یا تنظیم می‌کند. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [TextCapType](../../com.aspose.slides/textcaptype).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

نوع خط‌خربش متن را برمی‌گرداند یا تنظیم می‌کند. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**بازمی‌گرداند:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

نوع خط‌خربش متن را برمی‌گرداند یا تنظیم می‌کند. وراثت اعمال نمی‌شود. خواندنی/قابل‌نوشتن [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن به ارث می‌برد. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن به ارث می‌برد. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن به ارث می‌برد. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گرداند:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن به ارث می‌برد. خواندنی/قابل‌نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

ارتفاع قلم یک بخش را برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنای عدم تعریف ارتفاع است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن  float .

**بازمی‌گرداند:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

ارتفاع قلم یک بخش را برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنای عدم تعریف ارتفاع است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنای عدم تعریف قلم است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنای عدم تعریف قلم است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنای عدم تعریف قلم است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنای عدم تعریف قلم است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنای عدم تعریف قلم است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنای عدم تعریف قلم است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنای عدم تعریف قلم است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنای عدم تعریف قلم است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

متن صدری یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. مقدار از -100٪ (زیرنویس) تا 100٪ (صدری). **Float.NaN** به معنای عدم تعریف مقدار است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن  float .

**بازمی‌گرداند:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

متن صدری یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. مقدار از -100٪ (زیرنویس) تا 100٪ (صدری). **Float.NaN** به معنای عدم تعریف مقدار است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود، برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنای عدم تعریف مقدار است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن  float .

**بازمی‌گرداند:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود، برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنای عدم تعریف مقدار است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

شناسه زبان بررسی‌گر را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املا و دستور استفاده می‌شود. خواندنی/قابل‌نوشتن String.

**بازمی‌گرداند:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

شناسه زبان بررسی‌گر را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املا و دستور استفاده می‌شود. خواندنی/قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

شناسه زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن String.

**بازمی‌گرداند:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

شناسه زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. خوانдنی/قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

مقدار افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنای عدم تعریف مقدار است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن  float .

**بازمی‌گرداند:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

مقدار افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به معنای عدم تعریف مقدار است و باید از Master ارث برده شود. خواندنی/قابل‌نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

دریافت یا تنظیم مقداری که نشان می‌دهد آیا غلط‌گیری برای بخش متن فعال است یا نه. وقتی این ویژگی به false تنظیم شود، بررسی املا برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، غلط‌گیری مجاز است. مقدار پیش‌فرض false است.

**بازمی‌گرداند:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

دریافت یا تنظیم مقداری که نشان می‌دهد آیا غلط‌گیری برای بخش متن فعال است یا نه. وقتی این ویژگی به false تنظیم شود، بررسی املا برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، غلط‌گیری مجاز است. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | boolean |  |

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
boolean

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | boolean |  |