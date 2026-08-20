---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: هذه الفئة تحتوي على خصائص تنسيق جزء النص.
type: docs
url: /ar/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

--------------------

تُستخدم هذه الفئة لإرجاع وتعديل خصائص تنسيق جزء النص المُعّرفة للجزء المعين. هذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذلك في معظم الحالات ستحصل على قيم تعني "غير محددة".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) التي تعيد مثالًا من [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | تُرجع خصائص LineFormat لتحديد حدود النص. |
| [getFillFormat()](#getFillFormat--) | تُرجع خصائص FillFormat للنص. |
| [getEffectFormat()](#getEffectFormat--) | تُرجع خصائص EffectFormat للنص. |
| [getHighlightColor()](#getHighlightColor--) | تُرجع اللون المستخدم لتحديد النص. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | تُرجع خصائص LineFormat المستخدمة لتحديد خط التسطير. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | تُرجع خصائص FillFormat لخط التسطير. |
| [getFontBold()](#getFontBold--) | يحدد ما إذا كان الخط عريضًا. |
| [setFontBold(byte value)](#setFontBold-byte-) | يحدد ما إذا كان الخط عريضًا. |
| [getFontItalic()](#getFontItalic--) | يحدد ما إذا كان الخط مائلًا. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | يحدد ما إذا كان الخط مائلًا. |
| [getKumimoji()](#getKumimoji--) | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. |
| [getNormaliseHeight()](#getNormaliseHeight--) | يحدد ما إذا كان يجب تطبيع ارتفاع النص. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | يحدد ما إذا كان يجب تطبيع ارتفاع النص. |
| [getProofDisabled()](#getProofDisabled--) | يحدد ما إذا كان لا ينبغي تدقيق النص. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | يحدد ما إذا كان لا ينبغي تدقيق النص. |
| [getFontUnderline()](#getFontUnderline--) | تُرجع أو تُحدد نوع تسطير النص. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | تُرجع أو تُحدد نوع تسطير النص. |
| [getTextCapType()](#getTextCapType--) | تُرجع أو تُحدد نوع تحويل الحروف في النص. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | تُرجع أو تُحدد نوع تحويل الحروف في النص. |
| [getStrikethroughType()](#getStrikethroughType--) | تُرجع أو تُحدد نوع الشطب في النص. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | تُرجع أو تُحدد نوع الشطب في النص. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | يحدد ما إذا كان نمط التسطير يحتوي على خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | يحدد ما إذا كان نمط التسطير يحتوي على خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | يحدد ما إذا كان نمط التسطير يحتوي على خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | يحدد ما إذا كان نمط التسطير يحتوي على خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. |
| [getFontHeight()](#getFontHeight--) | تُرجع أو تُحدد ارتفاع الخط لجزء من النص. |
| [setFontHeight(float value)](#setFontHeight-float-) | تُرجع أو تُحدد ارتفاع الخط لجزء من النص. |
| [getLatinFont()](#getLatinFont--) | تُرجع أو تُحدد معلومات الخط اللاتيني. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | تُرجع أو تُحدد معلومات الخط اللاتيني. |
| [getEastAsianFont()](#getEastAsianFont--) | تُرجع أو تُحدد معلومات الخط الشرقي الآسيوي. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | تُرجع أو تُحدد معلومات الخط الشرقي الآسيوي. |
| [getComplexScriptFont()](#getComplexScriptFont--) | تُرجع أو تُحدد معلومات خط النص المعقّد. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | تُرجع أو تُحدد معلومات خط النص المعقّد. |
| [getSymbolFont()](#getSymbolFont--) | تُرجع أو تُحدد معلومات الخط الرمزي. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | تُرجع أو تُحدد معلومات الخط الرمزي. |
| [getEscapement()](#getEscapement--) | تُرجع أو تُحدد النص كقيد أعلى أو أسفل. |
| [setEscapement(float value)](#setEscapement-float-) | تُرجع أو تُحدد النص كقيد أعلى أو أسفل. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | تُرجع أو تُحدد الحد الأدنى لحجم الخط الذي يجب تشغيل التهجي له. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | تُرجع أو تُحدد الحد الأدنى لحجم الخط الذي يجب تشغيل التهجي له. |
| [getLanguageId()](#getLanguageId--) | تُرجع أو تُحدد معرف لغة التدقيق. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | تُرجع أو تُحدد معرف لغة التدقيق. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | تُرجع أو تُحدد معرف لغة بديلة. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | تُرجع أو تُحدد معرف لغة بديلة. |
| [getSpacing()](#getSpacing--) | تُرجع أو تُحدد الزيادة في تباعد الأحرف. |
| [setSpacing(float value)](#setSpacing-float-) | تُرجع أو تُحدد الزيادة في تباعد الأحرف. |
| [getSpellCheck()](#getSpellCheck--) | تحصل أو تُحدد قيمة تدل على ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | تحصل أو تُحدد قيمة تدل على ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

تُرجع خصائص LineFormat لتحديد حدود النص. لا يتم تطبيق الوراثة. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

تُرجع خصائص FillFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

تُرجع خصائص EffectFormat للنص. لا يتم تطبيق الوراثة. قراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**الإرجاع:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

تُرجع اللون المستخدم لتحديد النص. لا يتم تطبيق الوراثة. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

تُرجع خصائص LineFormat المستخدمة لتحديد خط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

تُرجع خصائص FillFormat لخط التسطير. لا يتم تطبيق الوراثة. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

يحدد ما إذا كان الخط عريضًا. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

يحدد ما إذا كان الخط مائلًا. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص العمودي الخاص باللغات الشرقية. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

يحدد ما إذا كان لا ينبغي تدقيق النص. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

يحدد ما إذا كان لا ينبغي تدقيق النص. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

تُرجع أو تُحدد نوع تسطير النص. لا يتم تطبيق الوراثة. قراءة/كتابة [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**الإرجاع:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

تُرجع أو تُحدد نوع تسطير النص. لا يتم تطبيق الوراثة. قراءة/كتابة [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

تُرجع أو تُحدد نوع تحويل الحروف في النص. لا يتم تطبيق الوراثة. قراءة/كتابة [TextCapType](../../com.aspose.slides/textcaptype).

**الإرجاع:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

تُرجع أو تُحدد نوع تحويل الحروف في النص. لا يتم تطبيق الوراثة. قراءة/كتابة [TextCapType](../../com.aspose.slides/textcaptype).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

تُرجع أو تُحدد نوع الشطب في النص. لا يتم تطبيق الوراثة. قراءة/كتابة [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**الإرجاع:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

تُرجع أو تُحدد نوع الشطب في النص. لا يتم تطبيق الوراثة. قراءة/كتابة [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

يحدد ما إذا كان نمط التسطير يحتوي على خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

يحدد ما إذا كان نمط التسطير يحتوي على خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

يحدد ما إذا كان نمط التسطير يحتوي على خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

يحدد ما إذا كان نمط التسطير يحتوي على خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

تُرجع أو تُحدد ارتفاع الخط لجزء من النص. **Float.NaN** يعني أن الارتفاع غير محدد ويجب وراثته من القالب. قراءة/كتابة float.

**الإرجاع:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

تُرجع أو تُحدد ارتفاع الخط لجزء من النص. **Float.NaN** يعني أن الارتفاع غير محدد ويجب وراثته من القالب. قراءة/كتابة float.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

تُرجع أو تُحدد معلومات الخط اللاتيني. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

تُرجع أو تُحدد معلومات الخط اللاتيني. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

تُرجع أو تُحدد معلومات الخط الشرقي الآسيوي. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

تُرجع أو تُحدد معلومات الخط الشرقي الآسيوي. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

تُرجع أو تُحدد معلومات خط النص المعقّد. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

تُرجع أو تُحدد معلومات خط النص المعقّد. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

تُرجع أو تُحدد معلومات الخط الرمزي. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

تُرجع أو تُحدد معلومات الخط الرمزي. القيمة Null تعني أن الخط غير محدد ويجب وراثته من القالب. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

تُرجع أو تُحدد النص كقيد أعلى أو أسفل. القيمة من -100% (قيد أسفل) إلى 100% (قيد أعلى). **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من القالب. قراءة/كتابة float.

**الإرجاع:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

تُرجع أو تُحدد النص كقيد أعلى أو أسفل. القيمة من -100% (قيد أسفل) إلى 100% (قيد أعلى). **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من القالب. قراءة/كتابة float.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

تُرجع أو تُحدد الحد الأدنى لحجم الخط الذي يجب تشغيل التهجي له. **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من القالب. قراءة/كتابة float.

**الإرجاع:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

تُرجع أو تُحدد الحد الأدنى لحجم الخط الذي يجب تشغيل التهجي له. **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من القالب. قراءة/كتابة float.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

تُرجع أو تُحدد معرف لغة التدقيق. تُستخدم لتدقيق الإملاء والقواعد. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

تُرجع أو تُحدد معرف لغة التدقيق. تُستخدم لتدقيق الإملاء والقواعد. قراءة/كتابة String.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

تُرجع أو تُحدد معرف لغة بديلة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

تُرجع أو تُحدد معرف لغة بديلة. قراءة/كتابة String.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

تُرجع أو تُحدد الزيادة في تباعد الأحرف. **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من القالب. قراءة/كتابة float.

**الإرجاع:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

تُرجع أو تُحدد الزيادة في تباعد الأحرف. **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من القالب. قراءة/كتابة float.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

تحصل أو تُحدد قيمة تدل على ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. عندما تُعيّن هذه الخاصية إلى false، يتم كتم تدقيق الإملاء لعناصر النص. عندما تُعيّن إلى true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // الوصول إلى الجزء الأول من النص داخل الشكل الأول في الشريحة الأولى
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // تمكين تدقيق الإملاء لهذا الجزء من النص
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

تحصل أو تُحدد قيمة تدل على ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. عندما تُعيّن هذه الخاصية إلى false، يتم كتم تدقيق الإملاء لعناصر النص. عندما تُعيّن إلى true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // الوصول إلى الجزء الأول من النص داخل الشكل الأول في الشريحة الأولى
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // تمكين تدقيق الإملاء لهذا الجزء من النص
>      portion.getPortionFormat().setSpellCheck(true);
>      // حفظ العرض التقديمي المعدل
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |