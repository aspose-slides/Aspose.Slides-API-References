---
title: IBasePortionFormat
second_title: Aspose.Slides لـ Android عبر مرجع API جافا
description: هذه الفئة تحتوي على خصائص تنسيق جزء النص.
type: docs
url: /ar/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

--------------------

تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق جزء النص المحدد للجزء المعين. يعني ذلك عدم تطبيق الوراثة عند الحصول على القيم، ولذلك في الغالب ستحصل على قيم تعني "غير معرف".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) التي تُعيد مثيل [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | يعيد خصائص LineFormat لتحديد حدود النص. |
| [getFillFormat()](#getFillFormat--) | يعيد خصائص FillFormat للنص. |
| [getEffectFormat()](#getEffectFormat--) | يعيد خصائص EffectFormat للنص. |
| [getHighlightColor()](#getHighlightColor--) | يعيد اللون المستخدم لتسليط الضوء على النص. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | يعيد خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | يعيد خصائص FillFormat لخط التسطير. |
| [getFontBold()](#getFontBold--) | يحدد ما إذا كان الخط عريضًا. |
| [setFontBold(byte value)](#setFontBold-byte-) | يحدد ما إذا كان الخط عريضًا. |
| [getFontItalic()](#getFontItalic--) | يحدد ما إذا كان الخط مائلًا. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | يحدد ما إذا كان الخط مائلًا. |
| [getKumimoji()](#getKumimoji--) | يحدد ما إذا كان يجب أن تتجاهل الأرقام تخطيط النص العمودي الخاص باللغات الشرقية. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | يحدد ما إذا كان يجب أن تتجاهل الأرقام تخطيط النص العمودي الخاص باللغات الشرقية. |
| [getNormaliseHeight()](#getNormaliseHeight--) | يحدد ما إذا كان يجب تطبيع ارتفاع النص. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | يحدد ما إذا كان يجب تطبيع ارتفاع النص. |
| [getProofDisabled()](#getProofDisabled--) | يحدد ما إذا كان لا ينبغي تدقيق النص. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | يحدد ما إذا كان لا ينبغي تدقيق النص. |
| [getFontUnderline()](#getFontUnderline--) | يعيد أو يضبط نوع تسطير النص. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | يعيد أو يضبط نوع تسطير النص. |
| [getTextCapType()](#getTextCapType--) | يعيد أو يضبط نوع تحويل النص إلى أحرف كبيرة. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | يعيد أو يضبط نوع تحويل النص إلى أحرف كبيرة. |
| [getStrikethroughType()](#getStrikethroughType--) | يعيد أو يضبط نوع الشطب للنص. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | يعيد أو يضبط نوع الشطب للنص. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. |
| [getFontHeight()](#getFontHeight--) | يعيد أو يضبط ارتفاع الخط للجزء. |
| [setFontHeight(float value)](#setFontHeight-float-) | يعيد أو يضبط ارتفاع الخط للجزء. |
| [getLatinFont()](#getLatinFont--) | يعيد أو يضبط معلومات الخط اللاتيني. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | يعيد أو يضبط معلومات الخط اللاتيني. |
| [getEastAsianFont()](#getEastAsianFont--) | يعيد أو يضبط معلومات الخط الآسيوي الشرقي. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | يعيد أو يضبط معلومات الخط الآسيوي الشرقي. |
| [getComplexScriptFont()](#getComplexScriptFont--) | يعيد أو يضبط معلومات الخط للكتابة المعقدة. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | يعيد أو يضبط معلومات الخط للكتابة المعقدة. |
| [getSymbolFont()](#getSymbolFont--) | يعيد أو يضبط معلومات الخط الرمزي. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | يعيد أو يضبط معلومات الخط الرمزي. |
| [getEscapement()](#getEscapement--) | يعيد أو يضبط النص كحرف فوقي أو سفلي. |
| [setEscapement(float value)](#setEscapement-float-) | يعيد أو يضبط النص كحرف فوقي أو سفلي. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | يعيد أو يضبط الحد الأدنى لحجم الخط الذي يتم فيه تشغيل التقريب. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | يعيد أو يضبط الحد الأدنى لحجم الخط الذي يتم فيه تشغيل التقريب. |
| [getLanguageId()](#getLanguageId--) | يعيد أو يضبط معرف لغة التدقيق. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | يعيد أو يضبط معرف لغة التدقيق. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | يعيد أو يضبط معرف لغة بديلة. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | يعيد أو يضبط معرف لغة بديلة. |
| [getSpacing()](#getSpacing--) | يعيد أو يضبط مقدار زيادة المسافة بين الأحرف. |
| [setSpacing(float value)](#setSpacing-float-) | يعيد أو يضبط مقدار زيادة المسافة بين الأحرف. |
| [getSpellCheck()](#getSpellCheck--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً للجزء النصي. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً للجزء النصي. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

يعيد خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. للقراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

يعيد خصائص FillFormat للنص. لا يتم تطبيق الوراثة. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

يعيد خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. للقراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**الإرجاع:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

يعيد اللون المستخدم لتسليط الضوء على النص. لا يتم تطبيق الوراثة. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

يعيد خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. لا يتم تطبيق الوراثة. للقراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

يعيد خصائص FillFormat لخط التسطير. لا يتم تطبيق الوراثة. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

يحدد ما إذا كان يجب أن تتجاهل الأرقام تخطيط النص العمودي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

يحدد ما إذا كان يجب أن تتجاهل الأرقام تخطيط النص العمودي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

يحدد ما إذا كان لا ينبغي تدقيق النص. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

يحدد ما إذا كان لا ينبغي تدقيق النص. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

يعيد أو يضبط نوع تسطير النص. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**الإرجاع:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

يعيد أو يضبط نوع تسطير النص. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

يعيد أو يضبط نوع تحويل النص إلى أحرف كبيرة. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [TextCapType](../../com.aspose.slides/textcaptype).

**الإرجاع:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

يعيد أو يضبط نوع تحويل النص إلى أحرف كبيرة. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [TextCapType](../../com.aspose.slides/textcaptype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

يعيد أو يضبط نوع الشطب للنص. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**الإرجاع:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

يعيد أو يضبط نوع الشطب للنص. لا يتم تطبيق الوراثة. قابل للقراءة والكتابة [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

يعيد أو يضبط ارتفاع الخط للجزء. **Float.NaN** يعني أن الارتفاع غير معرف ويجب توريثه من القالب الرئيسي. قابل للقراءة والكتابة float.

**الإرجاع:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

يعيد أو يضبط ارتفاع الخط للجزء. **Float.NaN** يعني أن الارتفاع غير معرف ويجب توريثه من القالب الرئيسي. قابل للقراءة والكتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

يعيد أو يضبط معلومات الخط اللاتيني. القيمة Null تعني أن الخط غير معرف ويجب توريثه من القالب الرئيسي. قابل للقراءة والكتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

يعيد أو يضبط معلومات الخط اللاتيني. القيمة Null تعني أن الخط غير معرف ويجب توريثه من القالب الرئيسي. قابل للقراءة والكتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

يعيد أو يضبط معلومات الخط الآسيوي الشرقي. القيمة Null تعني أن الخط غير معرف ويجب توريثه من القالب الرئيسي. قابل للقراءة والكتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

يعيد أو يضبط معلومات الخط الآسيوي الشرقي. القيمة Null تعني أن الخط غير معرف ويجب توريثه من القالب الرئيسي. قابل للقراءة والكتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

يعيد أو يضبط معلومات الخط للكتابة المعقدة. القيمة Null تعني أن الخط غير معرف ويجب توريثه من القالب الرئيسي. قابل للقراءة والكتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

يعيد أو يضبط معلومات الخط للكتابة المعقدة. القيمة Null تعني أن الخط غير معرف ويجب توريثه من القالب الرئيسي. قابل للقراءة والكتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

يعيد أو يضبط معلومات الخط الرمزي. القيمة Null تعني أن الخط غير معرف ويجب توريثه من القالب الرئيسي. قابل للقراءة والكتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

يعيد أو يضبط معلومات الخط الرمزي. القيمة Null تعني أن الخط غير معرف ويجب توريثه من القالب الرئيسي. قابل للقراءة والكتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

يعيد أو يضبط النص كحرف فوقي أو سفلي. القيمة تتراوح من -100٪ (سفلي) إلى 100٪ (فوقي). **Float.NaN** يعني أن القيمة غير معرف ويجب توريثها من القالب الرئيسي. قابل للقراءة والكتابة float.

**الإرجاع:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

يعيد أو يضبط النص كحرف فوقي أو سفلي. القيمة تتراوح من -100٪ (سفلي) إلى 100٪ (فوقي). **Float.NaN** يعني أن القيمة غير معرف ويجب توريثها من القالب الرئيسي. قابل للقراءة والكتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

يعيد أو يضبط الحد الأدنى لحجم الخط الذي يتم فيه تشغيل التقريب. **Float.NaN** يعني أن القيمة غير معرف ويجب توريثها من القالب الرئيسي. قابل للقراءة والكتابة float.

**الإرجاع:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

يعيد أو يضبط الحد الأدنى لحجم الخط الذي يتم فيه تشغيل التقريب. **Float.NaN** يعني أن القيمة غير معرف ويجب توريثها من القالب الرئيسي. قابل للقراءة والكتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

يعيد أو يضبط معرف لغة التدقيق. تُستخدم لفحص الإملاء والقواعد. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

يعيد أو يضبط معرف لغة التدقيق. تُستخدم لفحص الإملاء والقواعد. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

يعيد أو يضبط معرف لغة بديلة. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

يعيد أو يضبط معرف لغة بديلة. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

يعيد أو يضبط مقدار زيادة المسافة بين الأحرف. **Float.NaN** يعني أن القيمة غير معرف ويجب توريثها من القالب الرئيسي. قابل للقراءة والكتابة float.

**الإرجاع:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

يعيد أو يضبط مقدار زيادة المسافة بين الأحرف. **Float.NaN** يعني أن القيمة غير معرف ويجب توريثها من القالب الرئيسي. قابل للقراءة والكتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً للجزء النصي. عندما تُعطى هذه الخاصية القيمة false، يتم كبت فحص الإملاء لعناصر النص. عندما تُعطى القيمة true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // الوصول إلى الجزء النصي الأول داخل الشكل الأول في الشريحة الأولى
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // تفعيل تدقيق الإملاء لهذا الجزء النصي
>      portion.getPortionFormat().setSpellCheck(true);
>      // حفظ العرض التقديمي المعدل
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً للجزء النصي. عندما تُعطى هذه الخاصية القيمة false، يتم كبت فحص الإملاء لعناصر النص. عندما تُعطى القيمة true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // الوصول إلى الجزء النصي الأول داخل الشكل الأول في الشريحة الأولى
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // تفعيل تدقيق الإملاء لهذا الجزء النصي
>      portion.getPortionFormat().setSpellCheck(true);
>      // حفظ العرض التقديمي المعدل
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |