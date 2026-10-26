---
title: BasePortionFormat
second_title: مرجع API لـ Aspose.Slides للـ Java
description: خصائص تنسيق جزء النص العامة.
type: docs
url: /ar/com.aspose.slides/baseportionformat/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)  
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

خصائص تنسيق جزء النص العامة.  
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | إرجاع خصائص LineFormat لتحديد حدود النص. |
| [getFillFormat()](#getFillFormat--) | إرجاع خصائص FillFormat للنص. |
| [getEffectFormat()](#getEffectFormat--) | إرجاع خصائص EffectFormat للنص. |
| [getHighlightColor()](#getHighlightColor--) | إرجاع اللون المستخدم لتسليط الضوء على النص. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | إرجاع خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | إرجاع خصائص FillFormat لخط التسطير. |
| [getFontBold()](#getFontBold--) | يحدد ما إذا كان الخط عريضًا. |
| [setFontBold(byte value)](#setFontBold-byte-) | يحدد ما إذا كان الخط عريضًا. |
| [getFontItalic()](#getFontItalic--) | يحدد ما إذا كان الخط مائلاً. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | يحدد ما إذا كان الخط مائلاً. |
| [getKumimoji()](#getKumimoji--) | يحدد ما إذا كان يجب تجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | يحدد ما إذا كان يجب تجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. |
| [getNormaliseHeight()](#getNormaliseHeight--) | يحدد ما إذا كان يجب تطبيع ارتفاع النص. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | يحدد ما إذا كان يجب تطبيع ارتفاع النص. |
| [getProofDisabled()](#getProofDisabled--) | يحدد ما إذا كان يجب عدم تدقيق النص. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | يحدد ما إذا كان يجب عدم تدقيق النص. |
| [getFontUnderline()](#getFontUnderline--) | إرجاع أو تعيين نوع تسطير النص. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | إرجاع أو تعيين نوع تسطير النص. |
| [getTextCapType()](#getTextCapType--) | إرجاع أو تعيين نوع تحويل الحروف للنص. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | إرجاع أو تعيين نوع تحويل الحروف للنص. |
| [getStrikethroughType()](#getStrikethroughType--) | إرجاع أو تعيين نوع الخط العابر للنص. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | إرجاع أو تعيين نوع الخط العابر للنص. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. |
| [getFontHeight()](#getFontHeight--) | إرجاع أو تعيين ارتفاع الخط للجزء. |
| [setFontHeight(float value)](#setFontHeight-float-) | إرجاع أو تعيين ارتفاع الخط للجزء. |
| [getLatinFont()](#getLatinFont--) | إرجاع أو تعيين معلومات الخط اللاتيني. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين معلومات الخط اللاتيني. |
| [getEastAsianFont()](#getEastAsianFont--) | إرجاع أو تعيين معلومات الخط الآسيوي الشرقي. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين معلومات الخط الآسيوي الشرقي. |
| [getComplexScriptFont()](#getComplexScriptFont--) | إرجاع أو تعيين معلومات الخط النصي المعقد. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين معلومات الخط النصي المعقد. |
| [getSymbolFont()](#getSymbolFont--) | إرجاع أو تعيين معلومات الخط الرمزي. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين معلومات الخط الرمزي. |
| [getEscapement()](#getEscapement--) | إرجاع أو تعيين النص المرتفع أو المخفض. |
| [setEscapement(float value)](#setEscapement-float-) | إرجاع أو تعيين النص المرتفع أو المخفض. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | إرجاع أو تعيين الحد الأدنى لحجم الخط الذي يُفعَّل عنده التدرج. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | إرجاع أو تعيين الحد الأدنى لحجم الخط الذي يُفعَّل عنده التدرج. |
| [getLanguageId()](#getLanguageId--) | إرجاع أو تعيين معرف لغة التدقيق. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | إرجاع أو تعيين معرف لغة التدقيق. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | إرجاع أو تعيين معرف لغة بديلة. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | إرجاع أو تعيين معرف لغة بديلة. |
| [getSpacing()](#getSpacing--) | إرجاع أو تعيين زيادة تباعد الأحرف. |
| [setSpacing(float value)](#setSpacing-float-) | إرجاع أو تعيين زيادة تباعد الأحرف. |
| [getSpellCheck()](#getSpellCheck--) | إرجاع أو تعيين قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعلًا للجزء النصي. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | إرجاع أو تعيين قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعلًا للجزء النصي. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**  
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

إرجاع خصائص LineFormat لتحديد حدود النص. لم يتم تطبيق الوراثة. للقراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

إرجاع خصائص FillFormat للنص. لم يتم تطبيق الوراثة. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

إرجاع خصائص EffectFormat للنص. لم يتم تطبيق الوراثة. للقراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**الإرجاع:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

إرجاع اللون المستخدم لتسليط الضوء على النص. لم يتم تطبيق الوراثة. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

إرجاع خصائص LineFormat المستخدمة لتحديد حدود خط التسطير. لم يتم تطبيق الوراثة. للقراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

إرجاع خصائص FillFormat لخط التسطير. لم يتم تطبيق الوراثة. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

يحدد ما إذا كان الخط عريضًا. لم يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

يحدد ما إذا كان الخط عريضًا. لم يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

يحدد ما إذا كان الخط مائلاً. لم يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

يحدد ما إذا كان الخط مائلاً. لم يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

يحدد ما إذا كان يجب تجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. لم يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

يحدد ما إذا كان يجب تجاهل تخطيط النص الرأسي الخاص باللغات الشرقية. لم يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

يحدد ما إذا كان يجب تطبيع ارتفاع النص. لم يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

يحدد ما إذا كان يجب تطبيع ارتفاع النص. لم يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

يحدد ما إذا كان يجب عدم تدقيق النص. لم يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

يحدد ما إذا كان يجب عدم تدقيق النص. لم يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

إرجاع أو تعيين نوع تسطير النص. لم يتم تطبيق الوراثة. قراءة/كتابة [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**الإرجاع:**  
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

إرجاع أو تعيين نوع تسطير النص. لم يتم تطبيق الوراثة. قراءة/كتابة [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

إرجاع أو تعيين نوع تحويل الحروف للنص. لم يتم تطبيق الوراثة. قراءة/كتابة [TextCapType](../../com.aspose.slides/textcaptype).

**الإرجاع:**  
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

إرجاع أو تعيين نوع تحويل الحروف للنص. لم يتم تطبيق الوراثة. قراءة/كتابة [TextCapType](../../com.aspose.slides/textcaptype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

إرجاع أو تعيين نوع الخط العابر للنص. لم يتم تطبيق الوراثة. قراءة/كتابة [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**الإرجاع:**  
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

إرجاع أو تعيين نوع الخط العابر للنص. لم يتم تطبيق الوراثة. قراءة/كتابة [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص LineFormat خاصة أو يرثها من خصائص LineFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

يحدد ما إذا كان نمط التسطير يمتلك خصائص FillFormat خاصة أو يرثها من خصائص FillFormat للنص. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

إرجاع أو تعيين ارتفاع الخط للجزء. **Float.NaN** يعني أن الارتفاع غير محدد ويجب وراثته من النموذج الأساسي. قراءة/كتابة  float .

**الإرجاع:**  
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

إرجاع أو تعيين ارتفاع الخط للجزء. **Float.NaN** يعني أن الارتفاع غير محدد ويجب وراثته من النموذج الأساسي. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

إرجاع أو تعيين معلومات الخط اللاتيني. القيمة Null تعني أن الخط غير محدد ويجب وراثته من النموذج الأساسي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

إرجاع أو تعيين معلومات الخط اللاتيني. القيمة Null تعني أن الخط غير محدد ويجب وراثته من النموذج الأساسي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

إرجاع أو تعيين معلومات الخط الآسيوي الشرقي. القيمة Null تعني أن الخط غير محدد ويجب وراثته من النموذج الأساسي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

إرجاع أو تعيين معلومات الخط الآسيوي الشرقي. القيمة Null تعني أن الخط غير محدد ويجب وراثته من النموذج الأساسي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

إرجاع أو تعيين معلومات الخط النصي المعقد. القيمة Null تعني أن الخط غير محدد ويجب وراثته من النموذج الأساسي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

إرجاع أو تعيين معلومات الخط النصي المعقد. القيمة Null تعني أن الخط غير محدد ويجب وراثته من النموذج الأساسي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

إرجاع أو تعيين معلومات الخط الرمزي. القيمة Null تعني أن الخط غير محدد ويجب وراثته من النموذج الأساسي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

إرجاع أو تعيين معلومات الخط الرمزي. القيمة Null تعني أن الخط غير محدد ويجب وراثته من النموذج الأساسي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

إرجاع أو تعيين النص المرتفع أو المخفض. القيمة من -100% (مخفض) إلى 100% (مرتفع). **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من النموذج الأساسي. قراءة/كتابة  float .

**الإرجاع:**  
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

إرجاع أو تعيين النص المرتفع أو المخفض. القيمة من -100% (مخفض) إلى 100% (مرتفع). **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من النموذج الأساسي. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

إرجاع أو تعيين الحد الأدنى لحجم الخط الذي يُفعَّل عنده التدرج. **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من النموذج الأساسي. قراءة/كتابة  float .

**الإرجاع:**  
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

إرجاع أو تعيين الحد الأدنى لحجم الخط الذي يُفعَّل عنده التدرج. **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من النموذج الأساسي. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

إرجاع أو تعيين معرف لغة التدقيق. يستخدم لتدقيق الإملاء والنحو. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

إرجاع أو تعيين معرف لغة التدقيق. يستخدم لتدقيق الإملاء والنحو. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

إرجاع أو تعيين معرف لغة بديلة. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

إرجاع أو تعيين معرف لغة بديلة. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

إرجاع أو تعيين زيادة تباعد الأحرف. **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من النموذج الأساسي. قراءة/كتابة  float .

**الإرجاع:**  
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

إرجاع أو تعيين زيادة تباعد الأحرف. **Float.NaN** يعني أن القيمة غير محددة ويجب وراثتها من النموذج الأساسي. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

إرجاع أو تعيين قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعلًا للجزء النصي. عندما تكون هذه الخاصية false يتم إيقاف فحص الإملاء لعناصر النص. عندما تكون true يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي false .

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

**الإرجاع:**  
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

إرجاع أو تعيين قيمة تشير إلى ما إذا كان التدقيق الإملائي مفعلًا للجزء النصي. عندما تكون هذه الخاصية false يتم إيقاف فحص الإملاء لعناصر النص. عندما تكون true يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي false .

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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |