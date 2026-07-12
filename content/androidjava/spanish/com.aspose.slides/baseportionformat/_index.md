---
title: BasePortionFormat
second_title: Aspose.Slides para Android a través de la API Java
description: Propiedades comunes de formato de porción de texto.
type: docs
url: /es/com.aspose.slides/baseportionformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Common text portion formatting properties.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Devuelve las propiedades LineFormat para el contorno del texto. |
| [getFillFormat()](#getFillFormat--) | Devuelve las propiedades FillFormat del texto. |
| [getEffectFormat()](#getEffectFormat--) | Devuelve las propiedades EffectFormat del texto. |
| [getHighlightColor()](#getHighlightColor--) | Devuelve el color usado para resaltar un texto. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Devuelve las propiedades LineFormat usadas para el contorno de la línea de subrayado. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Devuelve las propiedades FillFormat de la línea de subrayado. |
| [getFontBold()](#getFontBold--) | Determina si la fuente está en negrita. |
| [setFontBold(byte value)](#setFontBold-byte-) | Determina si la fuente está en negrita. |
| [getFontItalic()](#getFontItalic--) | Determina si la fuente está en cursiva. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Determina si la fuente está en cursiva. |
| [getKumimoji()](#getKumimoji--) | Determina si los números deben ignorar el diseño vertical de texto específico de lenguas orientales. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Determina si los números deben ignorar el diseño vertical de texto específico de lenguas orientales. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determina si la altura de un texto debe normalizarse. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Determina si la altura de un texto debe normalizarse. |
| [getProofDisabled()](#getProofDisabled--) | Determina si el texto no debe revisarse. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Determina si el texto no debe revisarse. |
| [getFontUnderline()](#getFontUnderline--) | Devuelve o establece el tipo de subrayado del texto. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Devuelve o establece el tipo de subrayado del texto. |
| [getTextCapType()](#getTextCapType--) | Devuelve o establece el tipo de capitalización del texto. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Devuelve o establece el tipo de capitalización del texto. |
| [getStrikethroughType()](#getStrikethroughType--) | Devuelve o establece el tipo de tachado de un texto. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Devuelve o establece el tipo de tachado de un texto. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. |
| [getFontHeight()](#getFontHeight--) | Devuelve o establece la altura de fuente de una porción. |
| [setFontHeight(float value)](#setFontHeight-float-) | Devuelve o establece la altura de fuente de una porción. |
| [getLatinFont()](#getLatinFont--) | Devuelve o establece la información de fuente latina. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Devuelve o establece la información de fuente latina. |
| [getEastAsianFont()](#getEastAsianFont--) | Devuelve o establece la información de fuente del este asiático. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Devuelve o establece la información de fuente del este asiático. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Devuelve o establece la información de fuente de script complejo. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Devuelve o establece la información de fuente de script complejo. |
| [getSymbolFont()](#getSymbolFont--) | Devuelve o establece la información de fuente simbólica. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Devuelve o establece la información de fuente simbólica. |
| [getEscapement()](#getEscapement--) | Devuelve o establece el texto en superíndice o subíndice. |
| [setEscapement(float value)](#setEscapement-float-) | Devuelve o establece el texto en superíndice o subíndice. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Devuelve o establece el tamaño de fuente mínimo, para el cual el kerning debe activarse. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Devuelve o establece el tamaño de fuente mínimo, para el cual el kerning debe activarse. |
| [getLanguageId()](#getLanguageId--) | Devuelve o establece el Id de un idioma de corrección. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Devuelve o establece el Id de un idioma de corrección. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Devuelve o establece el Id de un idioma alternativo. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Devuelve o establece el Id de un idioma alternativo. |
| [getSpacing()](#getSpacing--) | Devuelve o establece el incremento de espaciado entre caracteres. |
| [setSpacing(float value)](#setSpacing-float-) | Devuelve o establece el incremento de espaciado entre caracteres. |
| [getSpellCheck()](#getSpellCheck--) | Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Devuelve las propiedades LineFormat para el contorno del texto. No se aplica herencia. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Devuelve las propiedades FillFormat del texto. No se aplica herencia. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Devuelve las propiedades EffectFormat del texto. No se aplica herencia. Solo lectura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Devuelve:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Devuelve el color usado para resaltar un texto. No se aplica herencia. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Devuelve las propiedades LineFormat usadas para el contorno de la línea de subrayado. No se aplica herencia. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Devuelve las propiedades FillFormat de la línea de subrayado. No se aplica herencia. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Determina si la fuente está en negrita. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Determina si la fuente está en negrita. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Determina si la fuente está en cursiva. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Determina si la fuente está en cursiva. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Determina si los números deben ignorar el diseño vertical de texto específico de lenguas orientales. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Determina si los números deben ignorar el diseño vertical de texto específico de lenguas orientales. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Determina si la altura de un texto debe normalizarse. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Determina si la altura de un texto debe normalizarse. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Determina si el texto no debe revisarse. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Determina si el texto no debe revisarse. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. Lectura/escritura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Devuelve:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. Lectura/escritura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Devuelve o establece el tipo de capitalización del texto. No se aplica herencia. Lectura/escritura [TextCapType](../../com.aspose.slides/textcaptype).

**Devuelve:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Devuelve o establece el tipo de capitalización del texto. No se aplica herencia. Lectura/escritura [TextCapType](../../com.aspose.slides/textcaptype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Devuelve o establece el tipo de tachado de un texto. No se aplica herencia. Lectura/escritura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Devuelve:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Devuelve o establece el tipo de tachado de un texto. No se aplica herencia. Lectura/escritura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Devuelve o establece la altura de fuente de una porción. **Float.NaN** significa que la altura es indefinida y debe heredarse del Master. Lectura/escritura float.

**Devuelve:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Devuelve o establece la altura de fuente de una porción. **Float.NaN** significa que la altura es indefinida y debe heredarse del Master. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Devuelve o establece la información de fuente latina. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Devuelve o establece la información de fuente latina. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Devuelve o establece la información de fuente del este asiático. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Devuelve o establece la información de fuente del este asiático. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Devuelve o establece la información de fuente de script complejo. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Devuelve o establece la información de fuente de script complejo. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Devuelve o establece la información de fuente simbólica. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Devuelve o establece la información de fuente simbólica. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Devuelve o establece el texto en superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice). **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Devuelve:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Devuelve o establece el texto en superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice). **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Devuelve o establece el tamaño de fuente mínimo, para el cual el kerning debe activarse. **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Devuelve:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Devuelve o establece el tamaño de fuente mínimo, para el cual el kerning debe activarse. **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Devuelve o establece el Id de un idioma de corrección. Usado para comprobar ortografía y gramática. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Devuelve o establece el Id de un idioma de corrección. Usado para comprobar ortografía y gramática. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Devuelve o establece el Id de un idioma alternativo. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Devuelve o establece el Id de un idioma alternativo. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Devuelve o establece el incremento de espaciado entre caracteres. **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Devuelve:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Devuelve o establece el incremento de espaciado entre caracteres. **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las revisiones ortográficas de los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es false.

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

**Devuelve:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las revisiones ortográficas de los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es false.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |