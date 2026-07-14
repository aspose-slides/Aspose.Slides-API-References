---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: واجهة أساسية للكائنات غير القابلة للتغيير التي تحتوي على خصائص تنسيق الجزء النصي الفعّالة.
type: docs
url: /ar/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

واجهة أساسية للكائنات غير القابلة للتغيير التي تحتوي على خصائص تنسيق الجزء النصي الفعّالة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | إرجاع خصائص LineFormat لتحديد حدود النص. |
| [getFillFormat()](#getFillFormat--) | إرجاع خصائص FillFormat للنص. |
| [getEffectFormat()](#getEffectFormat--) | إرجاع خصائص EffectFormat للنص. |
| [getHighlightColor()](#getHighlightColor--) | إرجاع اللون المستخدم لتظليل النص. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | إرجاع خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | إرجاع خصائص FillFormat لخط التسطير. |
| [getFontBold()](#getFontBold--) | تحديد ما إذا كان الخط عريضًا. |
| [getFontItalic()](#getFontItalic--) | تحديد ما إذا كان الخط مائلًا. |
| [getKumimoji()](#getKumimoji--) | تحديد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. |
| [getNormaliseHeight()](#getNormaliseHeight--) | تحديد ما إذا كان يجب تطبيع ارتفاع النص. |
| [getProofDisabled()](#getProofDisabled--) | تحديد ما إذا كان يجب عدم تدقيق النص. |
| [getFontUnderline()](#getFontUnderline--) | إرجاع نوع تسطير النص. |
| [getTextCapType()](#getTextCapType--) | إرجاع نوع تحويل النص إلى أحرف كبيرة. |
| [getStrikethroughType()](#getStrikethroughType--) | إرجاع نوع الشطب للنص. |
| [getSmartTagClean()](#getSmartTagClean--) | تحديد ما إذا كان يجب مسح العلامة الذكية. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | تحديد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | تحديد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. |
| [getFontHeight()](#getFontHeight--) | إرجاع ارتفاع الخط للجزء النصي، بالنقاط. |
| [getLatinFont()](#getLatinFont--) | إرجاع معلومات الخط اللاتيني. |
| [getEastAsianFont()](#getEastAsianFont--) | إرجاع معلومات الخط الشرقي الآسيوي. |
| [getComplexScriptFont()](#getComplexScriptFont--) | إرجاع معلومات الخط للكتابة المركبة. |
| [getSymbolFont()](#getSymbolFont--) | إرجاع معلومات الخط الرمزي. |
| [getEscapement()](#getEscapement--) | إرجاع النص المرتفع أو المنخفض. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | إرجاع الحد الأدنى لحجم الخط الذي يتم فيه تشغيل الضبط بين الحروف. |
| [getLanguageId()](#getLanguageId--) | إرجاع معرف اللغة. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | إرجاع معرف اللغة البديلة. |
| [getSpacing()](#getSpacing--) | إرجاع الزيادة في تباعد الأحرف، بالنقاط. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

إرجاع خصائص LineFormat لتحديد حدود النص. للقراءة فقط [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**القيمة المرجعة:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

إرجاع خصائص FillFormat للنص. للقراءة فقط [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**القيمة المرجعة:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

إرجاع خصائص EffectFormat للنص. للقراءة فقط [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**القيمة المرجعة:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```

إرجاع اللون المستخدم لتظليل النص. للقراءة فقط java.lang.Integer.

**القيمة المرجعة:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

إرجاع خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. للقراءة فقط [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**القيمة المرجعة:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

إرجاع خصائص FillFormat لخط التسطير. للقراءة فقط [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**القيمة المرجعة:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

تحديد ما إذا كان الخط عريضًا. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

تحديد ما إذا كان الخط مائلًا. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

تحديد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

تحديد ما إذا كان يجب تطبيع ارتفاع النص. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

تحديد ما إذا كان يجب عدم تدقيق النص. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

إرجاع نوع تسطير النص. للقراءة فقط [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**القيمة المرجعة:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

إرجاع نوع تحويل النص إلى أحرف كبيرة. للقراءة فقط [TextCapType](../../com.aspose.slides/textcaptype).

**القيمة المرجعة:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

إرجاع نوع الشطب للنص. للقراءة فقط [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**القيمة المرجعة:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

تحديد ما إذا كان يجب مسح العلامة الذكية. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

تحديد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

تحديد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

إرجاع ارتفاع الخط للجزء النصي، بالنقاط. للقراءة فقط float.

**القيمة المرجعة:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

إرجاع معلومات الخط اللاتيني. للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**القيمة المرجعة:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

إرجاع معلومات الخط الشرقي الآسيوي. للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**القيمة المرجعة:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

إرجاع معلومات الخط للكتابة المركبة. للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**القيمة المرجعة:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

إرجاع معلومات الخط الرمزي. للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**القيمة المرجعة:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

إرجاع النص المرتفع أو المنخفض. القيمة من -100 % (منخفض) إلى 100 % (مرتفع). للقراءة فقط float.

**القيمة المرجعة:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

إرجاع الحد الأدنى لحجم الخط الذي يتم فيه تشغيل الضبط بين الحروف. للقراءة فقط float.

**القيمة المرجعة:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

إرجاع معرف اللغة. للقراءة فقط String.

**القيمة المرجعة:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

إرجاع معرف اللغة البديلة. للقراءة فقط String.

**القيمة المرجعة:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

إرجاع الزيادة في تباعد الأحرف، بالنقاط. للقراءة فقط float.

**القيمة المرجعة:**
float