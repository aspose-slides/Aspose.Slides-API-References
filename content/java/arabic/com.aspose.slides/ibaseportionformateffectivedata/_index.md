---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides لمرجع API لجافا
description: واجهة أساسية للكائنات غير القابلة للتعديل التي تحتوي على خصائص تنسيق الجزء النصي الفعّال.
type: docs
url: /ar/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

واجهة أساسية للكائنات غير القابلة للتعديل التي تحتوي على خصائص تنسيق الجزء النصي الفعّال.
## الأساليب

| Method | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | إرجاع خصائص LineFormat لتحديد النص. |
| [getFillFormat()](#getFillFormat--) | إرجاع خصائص FillFormat للنص. |
| [getEffectFormat()](#getEffectFormat--) | إرجاع خصائص EffectFormat للنص. |
| [getHighlightColor()](#getHighlightColor--) | إرجاع اللون المستخدم لتظليل النص. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | إرجاع خصائص LineFormat المستخدمة لتحديد خط التسطير. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | إرجاع خصائص FillFormat لخط التسطير. |
| [getFontBold()](#getFontBold--) | تحديد ما إذا كان الخط عريضًا. |
| [getFontItalic()](#getFontItalic--) | تحديد ما إذا كان الخط مائلًا. |
| [getKumimoji()](#getKumimoji--) | تحديد ما إذا كانت الأرقام يجب أن تتجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. |
| [getNormaliseHeight()](#getNormaliseHeight--) | تحديد ما إذا كان يجب تطبيع ارتفاع النص. |
| [getProofDisabled()](#getProofDisabled--) | تحديد ما إذا كان لا يجب تدقيق النص. |
| [getFontUnderline()](#getFontUnderline--) | إرجاع نوع تسطير النص. |
| [getTextCapType()](#getTextCapType--) | إرجاع نوع تحويل الحروف للنص. |
| [getStrikethroughType()](#getStrikethroughType--) | إرجاع نوع الشطب للنص. |
| [getSmartTagClean()](#getSmartTagClean--) | تحديد ما إذا كان يجب حذف الوسم الذكي. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | تحديد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | تحديد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. |
| [getFontHeight()](#getFontHeight--) | إرجاع ارتفاع الخط للجزء النصي، بالنقاط. |
| [getLatinFont()](#getLatinFont--) | إرجاع معلومات خط Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | إرجاع معلومات خط East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | إرجاع معلومات خط النص المعقّد. |
| [getSymbolFont()](#getSymbolFont--) | إرجاع معلومات الخط الرمزي. |
| [getEscapement()](#getEscapement--) | إرجاع النص كأعلى أو أسفل السطر. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | إرجاع الحد الأدنى لحجم الخط الذي يجب تشغيل الكيرن فيه. |
| [getLanguageId()](#getLanguageId--) | إرجاع معرف اللغة. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | إرجاع معرف اللغة البديلة. |
| [getSpacing()](#getSpacing--) | إرجاع زيادة تباعد الأحرف، بالنقاط. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

إرجاع خصائص LineFormat لتحديد النص. قراءة فقط [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**الإرجاع:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

إرجاع خصائص FillFormat للنص. قراءة فقط [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**الإرجاع:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

إرجاع خصائص EffectFormat للنص. قراءة فقط [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**الإرجاع:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)

### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

إرجاع اللون المستخدم لتظليل النص. قراءة فقط java.awt.Color.

**الإرجاع:**
java.awt.Color

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

إرجاع خصائص LineFormat المستخدمة لتحديد خط التسطير. قراءة فقط [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**الإرجاع:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

إرجاع خصائص FillFormat لخط التسطير. قراءة فقط [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**الإرجاع:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

تحديد ما إذا كان الخط عريضًا. قراءة فقط boolean.

**الإرجاع:**
boolean

### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

تحديد ما إذا كان الخط مائلًا. قراءة فقط boolean.

**الإرجاع:**
boolean

### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

تحديد ما إذا كانت الأرقام يجب أن تتجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. قراءة فقط boolean.

**الإرجاع:**
boolean

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

تحديد ما إذا كان يجب تطبيع ارتفاع النص. قراءة فقط boolean.

**الإرجاع:**
boolean

### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

تحديد ما إذا كان لا يجب تدقيق النص. قراءة فقط boolean.

**الإرجاع:**
boolean

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

إرجاع نوع تسطير النص. قراءة فقط [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**الإرجاع:**
byte

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

إرجاع نوع تحويل الحروف للنص. قراءة فقط [TextCapType](../../com.aspose.slides/textcaptype).

**الإرجاع:**
byte

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

إرجاع نوع الشطب للنص. قراءة فقط [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**الإرجاع:**
byte

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

تحديد ما إذا كان يجب حذف الوسم الذكي. قراءة فقط boolean.

**الإرجاع:**
boolean

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

تحديد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. قراءة فقط boolean.

**الإرجاع:**
boolean

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

تحديد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. قراءة فقط boolean.

**الإرجاع:**
boolean

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

إرجاع ارتفاع الخط للجزء النصي، بالنقاط. قراءة فقط float.

**الإرجاع:**
float

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

إرجاع معلومات خط Latin. قراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

إرجاع معلومات خط East Asian. قراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

إرجاع معلومات خط النص المعقّد. قراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

إرجاع معلومات الخط الرمزي. قراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

إرجاع النص كأعلى أو أسفل السطر. القيمة من -100% (أسفل السطر) إلى 100% (أعلى السطر). قراءة فقط float.

**الإرجاع:**
float

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

إرجاع الحد الأدنى لحجم الخط الذي يجب تشغيل الكيرن فيه. قراءة فقط float.

**الإرجاع:**
float

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

إرجاع معرف اللغة. قراءة فقط String.

**الإرجاع:**
java.lang.String

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

إرجاع معرف اللغة البديلة. قراءة فقط String.

**الإرجاع:**
java.lang.String

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

إرجاع زيادة تباعد الأحرف، بالنقاط. قراءة فقط float.

**الإرجاع:**
float