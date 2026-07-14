---
title: BasePortionFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: ویژگی‌های قالب‌بندی بخش متن مشترک.
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

ویژگی‌های قالب‌بندی بخش متن مشترک.

## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | خواص LineFormat را برای خط‌کشی متن برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | خواص FillFormat متن را برمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | خواص EffectFormat متن را برمی‌گرداند. |
| [getHighlightColor()](#getHighlightColor--) | رنگ مورد استفاده برای برجسته‌سازی متن را برمی‌گرداند. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | خواص LineFormat مورد استفاده برای خط‌کشی زیرخط را برمی‌گرداند. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | خواص FillFormat خط زیرخط را برمی‌گرداند. |
| [getFontBold()](#getFontBold--) | مشخص می‌کند آیا قلم توپر (bold) است. |
| [setFontBold(byte value)](#setFontBold-byte-) | مشخص می‌کند آیا قلم توپر (bold) است. |
| [getFontItalic()](#getFontItalic--) | مشخص می‌کند آیا قلم کج (italic) است. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | مشخص می‌کند آیا قلم کج (italic) است. |
| [getKumimoji()](#getKumimoji--) | مشخص می‌کند آیا اعداد باید چیدمان عمودی خاص زبان‌های شرقی متن را نادیده بگیرند. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | مشخص می‌کند آیا اعداد باید چیدمان عمودی خاص زبان‌های شرقی متن را نادیده بگیرند. |
| [getNormaliseHeight()](#getNormaliseHeight--) | مشخص می‌کند آیا ارتفاع متن باید نرمال شود. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | مشخص می‌کند آیا ارتفاع متن باید نرمال شود. |
| [getProofDisabled()](#getProofDisabled--) | مشخص می‌کند آیا متن نباید ویراستاری شود. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | مشخص می‌کند آیا متن نباید ویراستاری شود. |
| [getFontUnderline()](#getFontUnderline--) | نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getTextCapType()](#getTextCapType--) | نوع حروف بزرگ/کوچک متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | نوع حروف بزرگ/کوچک متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getStrikethroughType()](#getStrikethroughType--) | نوع خط‌خورده متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | نوع خط‌خورده متن را برمی‌گرداند یا تنظیم می‌کند. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن به ارث می‌برد. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن به ارث می‌برد. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن به ارث می‌برد. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن به ارث می‌برد. |
| [getFontHeight()](#getFontHeight--) | ارتفاع قلم بخش را برمی‌گرداند یا تنظیم می‌کند. |
| [setFontHeight(float value)](#setFontHeight-float-) | ارتفاع قلم بخش را برمی‌گرداند یا تنظیم می‌کند. |
| [getLatinFont()](#getLatinFont--) | اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. |
| [getEastAsianFont()](#getEastAsianFont--) | اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. |
| [getComplexScriptFont()](#getComplexScriptFont--) | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. |
| [getSymbolFont()](#getSymbolFont--) | اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. |
| [getEscapement()](#getEscapement--) | متن سوپرسکریپت یا ساب‌اسکریپت را برمی‌گرداند یا تنظیم می‌کند. |
| [setEscapement(float value)](#setEscapement-float-) | متن سوپرسکریپت یا ساب‌اسکریپت را برمی‌گرداند یا تنظیم می‌کند. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | حداقل اندازه قلم که برای آن کرنینگ فعال می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | حداقل اندازه قلم که برای آن کرنینگ فعال می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [getLanguageId()](#getLanguageId--) | شناسه زبان بازبینی را برمی‌گرداند یا تنظیم می‌کند. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | شناسه زبان بازبینی را برمی‌گرداند یا تنظیم می‌کند. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | شناسه زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | شناسه زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. |
| [getSpacing()](#getSpacing--) | مقدار افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. |
| [setSpacing(float value)](#setSpacing-float-) | مقدار افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. |
| [getSpellCheck()](#getSpellCheck--) | مقدار نشان‌دهنده این که آیا بررسی املایی برای بخش متن فعال است یا خیر را برمی‌گرداند یا تنظیم می‌کند. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | مقدار نشان‌دهنده این که آیا بررسی املایی برای بخش متن فعال است یا خیر را برمی‌گرداند یا تنظیم می‌کند. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**بازگشت:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

خواص LineFormat را برای خط‌کشی متن برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

خواص FillFormat متن را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

خواص EffectFormat متن را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**بازگشت:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

رنگ مورد استفاده برای برجسته‌سازی متن را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

خواص LineFormat مورد استفاده برای خط‌کشی زیرخط را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

خواص FillFormat خط زیرخط را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

مشخص می‌کند آیا قلم توپر (bold) است. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

مشخص می‌کند آیا قلم توپر (bold) است. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

مشخص می‌کند آیا قلم کج (italic) است. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

مشخص می‌کند آیا قلم کج (italic) است. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

مشخص می‌کند آیا اعداد باید چیدمان عمودی خاص زبان‌های شرقی متن را نادیده بگیرند. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

مشخص می‌کند آیا اعداد باید چیدمان عمودی خاص زبان‌های شرقی متن را نادیده بگیرند. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

مشخص می‌کند آیا ارتفاع متن باید نرمال شود. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

مشخص می‌کند آیا ارتفاع متن باید نرمال شود. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

مشخص می‌کند آیا متن نباید ویراستاری شود. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

مشخص می‌کند آیا متن نباید ویراستاری شود. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**بازگشت:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

نوع حروف بزرگ/کوچک متن را برمی‌گرداند یا تنظیم می‌کند. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [TextCapType](../../com.aspose.slides/textcaptype).

**بازگشت:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

نوع حروف بزرگ/کوچک متن را برمی‌گرداند یا تنظیم می‌کند. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [TextCapType](../../com.aspose.slides/textcaptype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

نوع خط‌خورده متن را برمی‌گرداند یا تنظیم می‌کند. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**بازگشت:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

نوع خط‌خورده متن را برمی‌گرداند یا تنظیم می‌کند. ارث‌بری اعمال نمی‌شود. قابل-خواندن/نوشتن [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن به ارث می‌برد. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن به ارث می‌برد. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن به ارث می‌برد. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن به ارث می‌برد. قابل-خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

ارتفاع قلم بخش را برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به این معنی است که ارتفاع تعریف نشده است و باید از Master به ارث برده شود. قابل-خواندن/نوشتن float .

**بازگشت:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

ارتفاع قلم بخش را برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به این معنی است که ارتفاع تعریف نشده است و باید از Master به ارث برده شود. قابل-خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

متن سوپرسکریپت یا ساب‌اسکریپت را برمی‌گرداند یا تنظیم می‌کند. مقدار از -100٪ (ساب‌اسکریپت) تا 100٪ (سوپرسکریپت). **Float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن float .

**بازگشت:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

متن سوپرسکریپت یا ساب‌اسکریپت را برمی‌گرداند یا تنظیم می‌کند. مقدار از -100٪ (ساب‌اسکریپت) تا 100٪ (سوپرسکریپت). **Float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

حداقل اندازه قلم که برای آن کرنینگ فعال می‌شود را برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن float .

**بازگشت:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

حداقل اندازه قلم که برای آن کرنینگ فعال می‌شود را برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

شناسه زبان بازبینی را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املاء و گرامر استفاده می‌شود. قابل-خواندن/نوشتن String.

**بازگشت:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

شناسه زبان بازبینی را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املاء و گرامر استفاده می‌شود. قابل-خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

شناسه زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن/نوشتن String.

**بازگشت:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

شناسه زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

مقدار افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن float .

**بازگشت:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

مقدار افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. **Float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل-خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

مقداری را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی املای عناصر متنی سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض false است.

**بازگشت:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

مقداری را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی املای عناصر متنی سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // دسترسی به اولین بخش متن داخل اولین شکل در اولین اسلاید
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // فعال‌سازی بررسی املائی برای این بخش متن
>      portion.getPortionFormat().setSpellCheck(true);
>      // ذخیرهٔ ارائه‌ی اصلاح‌شده
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
boolean

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // دسترسی به اولین بخش متن داخل اولین شکل در اولین اسلاید
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // فعال‌سازی بررسی املائی برای این بخش متن
>      portion.getPortionFormat().setSpellCheck(true);
>      // ذخیرهٔ ارائه‌ی اصلاح‌شده
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |