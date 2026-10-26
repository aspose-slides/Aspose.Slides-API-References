---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: رابط پایه برای اشیای غیرقابل تغییر که شامل خصوصیات قالب‌بندی مؤثر بخش متن هستند.
type: docs
url: /fa/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

رابط پایه برای اشیای غیرقابل تغییر که شامل خصوصیات قالب‌بندی مؤثر بخش متن هستند.

## متدها

| متد | توضیح |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | ویژگی‌های LineFormat برای خط‌کشی متن را برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | ویژگی‌های FillFormat متن را برمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | ویژگی‌های EffectFormat متن را برمی‌گرداند. |
| [getHighlightColor()](#getHighlightColor--) | رنگ مورد استفاده برای برجسته‌سازی متن را برمی‌گرداند. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | ویژگی‌های LineFormat مورد استفاده برای خط‌کشی زیرخط را برمی‌گرداند. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. |
| [getFontBold()](#getFontBold--) | تعیین می‌کند که آیا قلم توپر (bold) است. |
| [getFontItalic()](#getFontItalic--) | تعیین می‌کند که آیا قلم ایتالیک (italic) است. |
| [getKumimoji()](#getKumimoji--) | تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند. |
| [getNormaliseHeight()](#getNormaliseHeight--) | تعیین می‌کند که آیا ارتفاع متن باید نرمال‌سازی شود. |
| [getProofDisabled()](#getProofDisabled--) | تعیین می‌کند که آیا متن نباید صحت‌سنجی (proof) شود. |
| [getFontUnderline()](#getFontUnderline--) | نوع زیرخط متن را برمی‌گرداند. |
| [getTextCapType()](#getTextCapType--) | نوع سرمایه‌گذاری متن (capitalization) را برمی‌گرداند. |
| [getStrikethroughType()](#getStrikethroughType--) | نوع خط‌خورده (strikethrough) متن را برمی‌گرداند. |
| [getSmartTagClean()](#getSmartTagClean--) | تعیین می‌کند که آیا برچسب هوشمند (smart tag) باید پاک شود. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | تعیین می‌کند که آیا سبک زیرخط دارای خصوصیات LineFormat اختصاصی است یا از خصوصیات LineFormat متن ارث می‌برد. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | تعیین می‌کند که آیا سبک زیرخط دارای خصوصیات FillFormat اختصاصی است یا از خصوصیات FillFormat متن ارث می‌برد. |
| [getFontHeight()](#getFontHeight--) | ارتفاع قلم بخش متن را بر حسب پوینت برمی‌گرداند. |
| [getLatinFont()](#getLatinFont--) | اطلاعات قلم لاتین را برمی‌گرداند. |
| [getEastAsianFont()](#getEastAsianFont--) | اطلاعات قلم آسیای شرقی را برمی‌گرداند. |
| [getComplexScriptFont()](#getComplexScriptFont--) | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند. |
| [getSymbolFont()](#getSymbolFont--) | اطلاعات قلم نمادین را برمی‌گرداند. |
| [getEscapement()](#getEscapement--) | متن فوق‌نویس یا پایین‌نویس را برمی‌گرداند. مقدار از -100٪ (پایین‌نویس) تا 100٪ (فوق‌نویس). |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | حداقل اندازه قلم را برمی‌گرداند که برای آن کرنینگ فعال می‌شود. |
| [getLanguageId()](#getLanguageId--) | شناسه یک زبان را برمی‌گرداند. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | شناسه یک زبان جایگزین را برمی‌گرداند. |
| [getSpacing()](#getSpacing--) | افزایش فاصله بین حروف را بر حسب پوینت برمی‌گرداند. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

ویژگی‌های LineFormat برای خط‌کشی متن را برمی‌گرداند. فقط خواندنی [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**برمی‌گرداند:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

ویژگی‌های FillFormat متن را برمی‌گرداند. فقط خواندنی [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**برمی‌گرداند:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

ویژگی‌های EffectFormat متن را برمی‌گرداند. فقط خواندنی [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**برمی‌گرداند:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)

### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```

رنگ مورد استفاده برای برجسته‌سازی متن را برمی‌گرداند. فقط خواندنی java.lang.Integer.

**برمی‌گرداند:**
java.lang.Integer

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

ویژگی‌های LineFormat مورد استفاده برای خط‌کشی زیرخط را برمی‌گرداند. فقط خواندنی [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**برمی‌گرداند:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. فقط خواندنی [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**برمی‌گرداند:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

تعیین می‌کند که آیا قلم توپر (bold) است. فقط خواندنی boolean.

**برمی‌گرداند:**
boolean

### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

تعیین می‌کند که آیا قلم ایتالیک (italic) است. فقط خواندنی boolean.

**برمی‌گرداند:**
boolean

### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند. فقط خواندنی boolean.

**برمی‌گرداند:**
boolean

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

تعیین می‌کند که آیا ارتفاع متن باید نرمال‌سازی شود. فقط خواندنی boolean.

**برمی‌گرداند:**
boolean

### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

تعیین می‌کند که آیا متن نباید صحت‌سنجی (proof) شود. فقط خواندنی boolean.

**برمی‌گرداند:**
boolean

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

نوع زیرخط متن را برمی‌گرداند. فقط خواندنی [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**برمی‌گرداند:**
byte

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

نوع سرمایه‌گذاری متن (capitalization) را برمی‌گرداند. فقط خواندنی [TextCapType](../../com.aspose.slides/textcaptype).

**برمی‌گرداند:**
byte

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

نوع خط‌خورده (strikethrough) متن را برمی‌گرداند. فقط خواندنی [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**برمی‌گرداند:**
byte

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

تعیین می‌کند که آیا برچسب هوشمند (smart tag) باید پاک شود. فقط خواندنی boolean.

**برمی‌گرداند:**
boolean

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

تعیین می‌کند که آیا سبک زیرخط دارای خصوصیات LineFormat اختصاصی است یا از خصوصیات LineFormat متن ارث می‌برد. فقط خواندنی boolean.

**برمی‌گرداند:**
boolean

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

تعیین می‌کند که آیا سبک زیرخط دارای خصوصیات FillFormat اختصاصی است یا از خصوصیات FillFormat متن ارث می‌برد. فقط خواندنی boolean.

**برمی‌گرداند:**
boolean

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

ارتفاع قلم بخش متن را بر حسب پوینت برمی‌گرداند. فقط خواندنی float.

**برمی‌گرداند:**
float

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

اطلاعات قلم لاتین را برمی‌گرداند. فقط خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**برمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

اطلاعات قلم آسیای شرقی را برمی‌گرداند. فقط خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**برمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند. فقط خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**برمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

اطلاعات قلم نمادین را برمی‌گرداند. فقط خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**برمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

متن فوق‌نویس یا پایین‌نویس را برمی‌گرداند. مقدار از -100٪ (پایین‌نویس) تا 100٪ (فوق‌نویس). فقط خواندنی float.

**برمی‌گرداند:**
float

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

حداقل اندازه قلم را برمی‌گرداند که برای آن کرنینگ فعال می‌شود. فقط خواندنی float.

**برمی‌گرداند:**
float

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

شناسه یک زبان را برمی‌گرداند. فقط خواندنی String.

**برمی‌گرداند:**
java.lang.String

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

شناسه یک زبان جایگزین را برمی‌گرداند. فقط خواندنی String.

**برمی‌گرداند:**
java.lang.String

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

افزایش فاصله بین حروف را بر حسب پوینت برمی‌گرداند. فقط خواندنی float.

**برمی‌گرداند:**
float