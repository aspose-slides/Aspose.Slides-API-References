---
title: BasePortionFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: خصائص تنسيق جزء النص الشائعة.
type: docs
url: /ar/com.aspose.slides/baseportionformat/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)  
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

خصائص تنسيق جزء النص المشتركة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | يعيد خصائص LineFormat لتحديد حدود النص. |
| [getFillFormat()](#getFillFormat--) | يعيد خصائص FillFormat للنص. |
| [getEffectFormat()](#getEffectFormat--) | يعيد خصائص EffectFormat للنص. |
| [getHighlightColor()](#getHighlightColor--) | يعيد اللون المستخدم لتظليل النص. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | يعيد خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | يعيد خصائص FillFormat لخط التسطير. |
| [getFontBold()](#getFontBold--) | يحدد ما إذا كان الخط عريضًا. |
| [setFontBold(byte value)](#setFontBold-byte-) | يحدد ما إذا كان الخط عريضًا. |
| [getFontItalic()](#getFontItalic--) | يحدد ما إذا كان الخط مائلًا. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | يحدد ما إذا كان الخط مائلًا. |
| [getKumimoji()](#getKumimoji--) | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. |
| [getNormaliseHeight()](#getNormaliseHeight--) | يحدد ما إذا كان يجب تطبيع ارتفاع النص. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | يحدد ما إذا كان يجب تطبيع ارتفاع النص. |
| [getProofDisabled()](#getProofDisabled--) | يحدد ما إذا كان النص لا ينبغي تدقيقه. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | يحدد ما إذا كان النص لا ينبغي تدقيقه. |
| [getFontUnderline()](#getFontUnderline--) | يعيد أو يحدد نوع تسطير النص. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | يعيد أو يحدد نوع تسطير النص. |
| [getTextCapType()](#getTextCapType--) | يعيد أو يحدد نوع كتابة النص بالحروف الكبيرة. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | يعيد أو يحدد نوع كتابة النص بالحروف الكبيرة. |
| [getStrikethroughType()](#getStrikethroughType--) | يعيد أو يحدد نوع الشطب للنص. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | يعيد أو يحدد نوع الشطب للنص. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. |
| [getFontHeight()](#getFontHeight--) | يعيد أو يحدد ارتفاع الخط لجزء. |
| [setFontHeight(float value)](#setFontHeight-float-) | يعيد أو يحدد ارتفاع الخط لجزء. |
| [getLatinFont()](#getLatinFont--) | يعيد أو يحدد معلومات الخط اللاتيني. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | يعيد أو يحدد معلومات الخط اللاتيني. |
| [getEastAsianFont()](#getEastAsianFont--) | يعيد أو يحدد معلومات الخط الآسيوي الشرقي. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | يعيد أو يحدد معلومات الخط الآسيوي الشرقي. |
| [getComplexScriptFont()](#getComplexScriptFont--) | يعيد أو يحدد معلومات خط النص المعقد. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | يعيد أو يحدد معلومات خط النص المعقد. |
| [getSymbolFont()](#getSymbolFont--) | يعيد أو يحدد معلومات الخط الرمزي. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | يعيد أو يحدد معلومات الخط الرمزي. |
| [getEscapement()](#getEscapement--) | يعيد أو يحدد النص كمرتفع أو منخفض. |
| [setEscapement(float value)](#setEscapement-float-) | يعيد أو يحدد النص كمرتفع أو منخفض. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | يعيد أو يحدد الحد الأدنى لحجم الخط الذي يجب تشغيل الكيرنينج له. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | يعيد أو يحدد الحد الأدنى لحجم الخط الذي يجب تشغيل الكيرنينج له. |
| [getLanguageId()](#getLanguageId--) | يعيد أو يحدد معرف لغة التدقيق. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | يعيد أو يحدد معرف لغة التدقيق. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | يعيد أو يحدد معرف لغة بديلة. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | يعيد أو يحدد معرف لغة بديلة. |
| [getSpacing()](#getSpacing--) | يعيد أو يحدد ارتفاع الفاصل بين الأحرف. |
| [setSpacing(float value)](#setSpacing-float-) | يعيد أو يحدد ارتفاع الفاصل بين الأحرف. |
| [getSpellCheck()](#getSpellCheck--) | يحصل أو يحدد قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | يحصل أو يحدد قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**القيمة المرجعة:**  
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

يعيد خصائص LineFormat لتحديد حدود النص. لا يُطبق الوراثة. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**القيمة المرجعة:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

يعيد خصائص FillFormat للنص. لا يُطبق الوراثة. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**القيمة المرجعة:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

يعيد خصائص EffectFormat للنص. لا يُطبق الوراثة. قراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**القيمة المرجعة:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

يعيد اللون المستخدم لتظليل النص. لا يُطبق الوراثة. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

يعيد خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. لا يُطبق الوراثة. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**القيمة المرجعة:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

يعيد خصائص FillFormat لخط التسطير. لا يُطبق الوراثة. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**القيمة المرجعة:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

يحدد ما إذا كان الخط عريضًا. لا يُطبق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**  
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

يحدد ما إذا كان الخط عريضًا. لا يُطبق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

يحدد ما إذا كان الخط مائلًا. لا يُطبق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**  
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

يحدد ما إذا كان الخط مائلًا. لا يُطبق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. لا يُطبق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**  
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

يحدد ما إذا كان يجب على الأرقام تجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. لا يُطبق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يُطبق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**  
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

يحدد ما إذا كان يجب تطبيع ارتفاع النص. لا يُطبق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

يحدد ما إذا كان النص لا ينبغي تدقيقه. لا يُطبق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**  
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

يحدد ما إذا كان النص لا ينبغي تدقيقه. لا يُطبق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

يعيد أو يحدد نوع تسطير النص. لا يُطبق الوراثة. قراءة/كتابة [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**القيمة المرجعة:**  
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

يعيد أو يحدد نوع تسطير النص. لا يُطبق الوراثة. قراءة/كتابة [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

يعيد أو يحدد نوع كتابة النص بالحروف الكبيرة. لا يُطبق الوراثة. قراءة/كتابة [TextCapType](../../com.aspose.slides/textcaptype).

**القيمة المرجعة:**  
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

يعيد أو يحدد نوع كتابة النص بالحروف الكبيرة. لا يُطبق الوراثة. قراءة/كتابة [TextCapType](../../com.aspose.slides/textcaptype).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

يعيد أو يحدد نوع الشطب للنص. لا يُطبق الوراثة. قراءة/كتابة [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**القيمة المرجعة:**  
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

يعيد أو يحدد نوع الشطب للنص. لا يُطبق الوراثة. قراءة/كتابة [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**  
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat الخاصة به أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**  
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat الخاصة به أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

يعيد أو يحدد ارتفاع الخط لجزء. **Float.NaN** يعني أن الارتفاع غير معرف ويجب وراثته من الـ Master. قراءة/كتابة  float .

**القيمة المرجعة:**  
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

يعيد أو يحدد ارتفاع الخط لجزء. **Float.NaN** يعني أن الارتفاع غير معرف ويجب وراثته من الـ Master. قراءة/كتابة  float .

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

يعيد أو يحدد معلومات الخط اللاتيني. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**القيمة المرجعة:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

يعيد أو يحدد معلومات الخط اللاتيني. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

يعيد أو يحدد معلومات الخط الآسيوي الشرقي. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**القيمة المرجعة:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

يعيد أو يحدد معلومات الخط الآسيوي الشرقي. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

يعيد أو يحدد معلومات خط النص المعقد. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**القيمة المرجعة:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

يعيد أو يحدد معلومات خط النص المعقد. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

يعيد أو يحدد معلومات الخط الرمزي. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**القيمة المرجعة:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

يعيد أو يحدد معلومات الخط الرمزي. Null يعني أن الخط غير معرف ويجب وراثته من الـ Master. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

يعيد أو يحدد النص كمرتفع أو منخفض. القيمة من -100% (منخفض) إلى 100% (مرتفع). **Float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة/كتابة  float .

**القيمة المرجعة:**  
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

يعيد أو يحدد النص كمرتفع أو منخفض. القيمة من -100% (منخفض) إلى 100% (مرتفع). **Float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة/كتابة  float .

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

يعيد أو يحدد الحد الأدنى لحجم الخط الذي يجب تشغيل الكيرنينج له. **Float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة/كتابة  float .

**القيمة المرجعة:**  
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

يعيد أو يحدد الحد الأدنى لحجم الخط الذي يجب تشغيل الكيرنينج له. **Float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة/كتابة  float .

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

يعيد أو يحدد معرف لغة التدقيق. يستخدم لتدقيق الإملاء والقواعد. قراءة/كتابة String.

**القيمة المرجعة:**  
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

يعيد أو يحدد معرف لغة التدقيق. يستخدم لتدقيق الإملاء والقواعد. قراءة/كتابة String.

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

يعيد أو يحدد معرف لغة بديلة. قراءة/كتابة String.

**القيمة المرجعة:**  
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

يعيد أو يحدد معرف لغة بديلة. قراءة/كتابة String.

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

يعيد أو يحدد ارتفاع الفاصل بين الأحرف. **Float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة/كتابة  float .

**القيمة المرجعة:**  
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

يعيد أو يحدد ارتفاع الفاصل بين الأحرف. **Float.NaN** يعني أن القيمة غير معرفة ويجب وراثتها من الـ Master. قراءة/كتابة  float .

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

يحصل أو يحدد قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. عندما تكون هذه الخاصية false يتم إلغاء فحص الإملاء لعناصر النص. عندما تكون true يُسمح بتدقيق الإملاء. القيمة الافتراضية هي false.

**القيمة المرجعة:**  
boolean

--------------------

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

**القيمة المرجعة:**  
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

يحصل أو يحدد قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً لجزء النص. عندما تكون هذه الخاصية false يتم إلغاء فحص الإملاء لعناصر النص. عندما تكون true يُسمح بتدقيق الإملاء. القيمة الافتراضية هي false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // الوصول إلى الجزء الأول من النص داخل الشكل الأول على الشريحة الأولى
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // تمكين تدقيق الإملاء لهذا الجزء من النص
>      portion.getPortionFormat().setSpellCheck(true);
>      // حفظ العرض المعدل
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |