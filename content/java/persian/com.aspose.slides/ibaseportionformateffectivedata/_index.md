---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: رابط پایه برای اشیای غیرقابل تغییر که حاوی ویژگی‌های قالب‌بندی مؤثر بخش متن هستند.
type: docs
url: /fa/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

رابط پایه برای اشیای غیرقابل تغییر که حاوی ویژگی‌های قالب‌بندی مؤثر بخش متن هستند.
## متدها

| Method | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | ویژگی‌های LineFormat را برای حاشیه‌گذاری متن برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | ویژگی‌های FillFormat متن را برمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | ویژگی‌های EffectFormat متن را برمی‌گرداند. |
| [getHighlightColor()](#getHighlightColor--) | رنگ مورد استفاده برای برجسته‌سازی متن را برمی‌گرداند. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | ویژگی‌های LineFormat را که برای حاشیه‌گذاری خط زیرخط استفاده می‌شود برمی‌گرداند. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. |
| [getFontBold()](#getFontBold--) | تعیین می‌کند که آیا قلم توپر (bold) است. |
| [getFontItalic()](#getFontItalic--) | تعیین می‌کند که آیا قلم ایتالیک (itallic) است. |
| [getKumimoji()](#getKumimoji--) | تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند. |
| [getNormaliseHeight()](#getNormaliseHeight--) | تعیین می‌کند که آیا ارتفاع متن باید نرمال‌سازی شود. |
| [getProofDisabled()](#getProofDisabled--) | تعیین می‌کند که آیا متن نباید اصلاح شود. |
| [getFontUnderline()](#getFontUnderline--) | نوع زیرخط متن را برمی‌گرداند. |
| [getTextCapType()](#getTextCapType--) | نوع حروف بزرگ/کوچک متن را برمی‌گرداند. |
| [getStrikethroughType()](#getStrikethroughType--) | نوع خط‌خورده متن را برمی‌گرداند. |
| [getSmartTagClean()](#getSmartTagClean--) | تعیین می‌کند که آیا برچسب هوشمند باید تمیز شود. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا آن را از ویژگی‌های LineFormat متن به ارث می‌برد. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا آن را از ویژگی‌های FillFormat متن به ارث می‌برد. |
| [getFontHeight()](#getFontHeight--) | ارتفاع قلم بخش متن را بر حسب پوینت برمی‌گرداند. |
| [getLatinFont()](#getLatinFont--) | اطلاعات قلم لاتین را برمی‌گرداند. |
| [getEastAsianFont()](#getEastAsianFont--) | اطلاعات قلم آسیای شرقی را برمی‌گرداند. |
| [getComplexScriptFont()](#getComplexScriptFont--) | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند. |
| [getSymbolFont()](#getSymbolFont--) | اطلاعات قلم نمادین را برمی‌گرداند. |
| [getEscapement()](#getEscapement--) | متن فوقانی یا زیرنویس را برمی‌گرداند. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود برمی‌گرداند. |
| [getLanguageId()](#getLanguageId--) | شناسه یک زبان را برمی‌گرداند. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | شناسه یک زبان جایگزین را برمی‌گرداند. |
| [getSpacing()](#getSpacing--) | افزایش فاصله بین حروف را برحسب پوینت برمی‌گرداند. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

ویژگی‌های LineFormat را برای حاشیه‌گذاری متن برمی‌گرداند. فقط-خواندنی [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**باز می‌گردد:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

ویژگی‌های FillFormat متن را برمی‌گرداند. فقط-خواندنی [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**باز می‌گردد:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

ویژگی‌های EffectFormat متن را برمی‌گرداند. فقط-خواندنی [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**باز می‌گردد:**  
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

رنگ مورد استفاده برای برجسته‌سازی متن را برمی‌گرداند. فقط-خواندنی java.awt.Color.

**باز می‌گردد:**  
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

ویژگی‌های LineFormat را که برای حاشیه‌گذاری خط زیرخط استفاده می‌شود برمی‌گرداند. فقط-خواندنی [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**باز می‌گردد:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. فقط-خواندنی [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**باز می‌گردد:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

تعیین می‌کند که آیا قلم توپر (bold) است. فقط-خواندنی boolean.

**باز می‌گردد:**  
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

تعیین می‌کند که آیا قلم ایتالیک (itallic) است. فقط-خواندنی boolean.

**باز می‌گردد:**  
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند. فقط-خواندنی boolean.

**باز می‌گردد:**  
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

تعیین می‌کند که آیا ارتفاع متن باید نرمال‌سازی شود. فقط-خواندنی boolean.

**باز می‌گردد:**  
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

تعیین می‌کند که آیا متن نباید اصلاح شود. فقط-خواندنی boolean.

**باز می‌گردد:**  
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

نوع زیرخط متن را برمی‌گرداند. فقط-خواندنی [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**باز می‌گردد:**  
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

نوع حروف بزرگ/کوچک متن را برمی‌گرداند. فقط-خواندنی [TextCapType](../../com.aspose.slides/textcaptype).

**باز می‌گردد:**  
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

نوع خط‌خورده متن را برمی‌گرداند. فقط-خواندنی [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**باز می‌گردد:**  
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

تعیین می‌کند که آیا برچسب هوشمند باید تمیز شود. فقط-خواندنی boolean.

**باز می‌گردد:**  
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا آن را از ویژگی‌های LineFormat متن به ارث می‌برد. فقط-خواندنی boolean.

**باز می‌گردد:**  
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا آن را از ویژگی‌های FillFormat متن به ارث می‌برد. فقط-خواندنی boolean.

**باز می‌گردد:**  
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

ارتفاع قلم بخش متن را بر حسب پوینت برمی‌گرداند. فقط-خواندنی float.

**باز می‌گردد:**  
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

اطلاعات قلم لاتین را برمی‌گرداند. فقط-خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**باز می‌گردد:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

اطلاعات قلم آسیای شرقی را برمی‌گرداند. فقط-خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**باز می‌گردد:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند. فقط-خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**باز می‌گردد:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

اطلاعات قلم نمادین را برمی‌گرداند. فقط-خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**باز می‌گردد:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

متن فوقانی یا زیرنویس را برمی‌گرداند. مقدار از -100% (زیرنویس) تا 100% (فوقانی). فقط-خواندنی float.

**باز می‌گردد:**  
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود برمی‌گرداند. فقط-خواندنی float.

**باز می‌گردد:**  
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

شناسه یک زبان را برمی‌گرداند. فقط-خواندنی String.

**باز می‌گردد:**  
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

شناسه یک زبان جایگزین را برمی‌گرداند. فقط-خواندنی String.

**باز می‌گردد:**  
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

افزایش فاصله بین حروف را برحسب پوینت برمی‌گرداند. فقط-خواندنی float.

**باز می‌گردد:**  
float