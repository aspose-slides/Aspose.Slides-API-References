---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: Esta clase contiene las propiedades de formato de porción de texto.
type: docs
url: /es/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Esta clase contiene las propiedades de formato de porción de texto. A diferencia de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), todas las propiedades de esta clase son modificables.

--------------------

Esta clase se utiliza para obtener y manipular las propiedades de formato de porción de texto definidas para la porción particular. Esto significa que no se aplica herencia al obtener los valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".

Para obtener los valores de los parámetros de formato efectivos, incluidas las herencias, debe utilizar el método [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) que devuelve una instancia de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Métodos

| Método | Descripción |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Devuelve las propiedades LineFormat para el contorno del texto. |
| [getFillFormat()](#getFillFormat--) | Devuelve las propiedades FillFormat del texto. |
| [getEffectFormat()](#getEffectFormat--) | Devuelve las propiedades EffectFormat del texto. |
| [getHighlightColor()](#getHighlightColor--) | Devuelve el color utilizado para resaltar un texto. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Devuelve las propiedades LineFormat utilizadas para delinear la línea de subrayado. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Devuelve las propiedades FillFormat de la línea de subrayado. |
| [getFontBold()](#getFontBold--) | Determina si la fuente está en negrita. |
| [setFontBold(byte value)](#setFontBold-byte-) | Determina si la fuente está en negrita. |
| [getFontItalic()](#getFontItalic--) | Determina si la fuente está en cursiva. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Determina si la fuente está en cursiva. |
| [getKumimoji()](#getKumimoji--) | Determina si los números deben ignorar la disposición vertical del texto específica de idiomas orientales. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Determina si los números deben ignorar la disposición vertical del texto específica de idiomas orientales. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determina si la altura del texto debe normalizarse. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Determina si la altura del texto debe normalizarse. |
| [getProofDisabled()](#getProofDisabled--) | Determina si el texto no debe revisarse. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Determina si el texto no debe revisarse. |
| [getFontUnderline()](#getFontUnderline--) | Devuelve o establece el tipo de subrayado del texto. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Devuelve o establece el tipo de subrayado del texto. |
| [getTextCapType()](#getTextCapType--) | Devuelve o establece el tipo de capitalización del texto. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Devuelve o establece el tipo de capitalización del texto. |
| [getStrikethroughType()](#getStrikethroughType--) | Devuelve o establece el tipo de tachado del texto. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Devuelve o establece el tipo de tachado del texto. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. |
| [getFontHeight()](#getFontHeight--) | Devuelve o establece la altura de fuente de una porción. |
| [setFontHeight(float value)](#setFontHeight-float-) | Devuelve o establece la altura de fuente de una porción. |
| [getLatinFont()](#getLatinFont--) | Devuelve o establece la información de la fuente latina. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Devuelve o establece la información de la fuente latina. |
| [getEastAsianFont()](#getEastAsianFont--) | Devuelve o establece la información de la fuente de Asia Oriental. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Devuelve o establece la información de la fuente de Asia Oriental. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Devuelve o establece la información de la fuente de script complejo. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Devuelve o establece la información de la fuente de script complejo. |
| [getSymbolFont()](#getSymbolFont--) | Devuelve o establece la información de la fuente simbólica. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Devuelve o establece la información de la fuente simbólica. |
| [getEscapement()](#getEscapement--) | Devuelve o establece el texto en superíndice o subíndice. |
| [setEscapement(float value)](#setEscapement-float-) | Devuelve o establece el texto en superíndice o subíndice. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Devuelve o establece el tamaño de fuente mínimo, para el cual se debe activar el kerning. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Devuelve o establece el tamaño de fuente mínimo, para el cual se debe activar el kerning. |
| [getLanguageId()](#getLanguageId--) | Devuelve o establece el Id de un idioma de corrección. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Devuelve o establece el Id de un idioma de corrección. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Devuelve o establece el Id de un idioma alternativo. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Devuelve o establece el Id de un idioma alternativo. |
| [getSpacing()](#getSpacing--) | Devuelve o establece el incremento del espaciado entre caracteres. |
| [setSpacing(float value)](#setSpacing-float-) | Devuelve o establece el incremento del espaciado entre caracteres. |
| [getSpellCheck()](#getSpellCheck--) | Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Devuelve las propiedades LineFormat para el contorno del texto. No se aplica herencia. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Devuelve las propiedades FillFormat del texto. No se aplica herencia. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Devuelve las propiedades EffectFormat del texto. No se aplica herencia. Solo lectura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Devuelve:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Devuelve el color utilizado para resaltar un texto. No se aplica herencia. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Devuelve las propiedades LineFormat utilizadas para delinear la línea de subrayado. No se aplica herencia. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Devuelve las propiedades FillFormat de la línea de subrayado. No se aplica herencia. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Determina si la fuente está en negrita. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Determina si la fuente está en negrita. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Determina si la fuente está en cursiva. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Determina si la fuente está en cursiva. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Determina si los números deben ignorar la disposición vertical del texto específica de idiomas orientales. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Determina si los números deben ignorar la disposición vertical del texto específica de idiomas orientales. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Determina si la altura del texto debe normalizarse. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Determina si la altura del texto debe normalizarse. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Determina si el texto no debe revisarse. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Determina si el texto no debe revisarse. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. Lectura/escritura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Devuelve:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. Lectura/escritura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Devuelve o establece el tipo de capitalización del texto. No se aplica herencia. Lectura/escritura [TextCapType](../../com.aspose.slides/textcaptype).

**Devuelve:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Devuelve o establece el tipo de capitalización del texto. No se aplica herencia. Lectura/escritura [TextCapType](../../com.aspose.slides/textcaptype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Devuelve o establece el tipo de tachado del texto. No se aplica herencia. Lectura/escritura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Devuelve:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Devuelve o establece el tipo de tachado del texto. No se aplica herencia. Lectura/escritura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Devuelve o establece la altura de fuente de una porción. **Float.NaN** significa que la altura es indefinida y debe heredarse del Master. Lectura/escritura float.

**Devuelve:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Devuelve o establece la altura de fuente de una porción. **Float.NaN** significa que la altura es indefinida y debe heredarse del Master. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Devuelve o establece la información de la fuente latina. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Devuelve o establece la información de la fuente latina. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Devuelve o establece la información de la fuente de Asia Oriental. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Devuelve o establece la información de la fuente de Asia Oriental. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Devuelve o establece la información de la fuente de script complejo. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Devuelve o establece la información de la fuente de script complejo. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Devuelve o establece la información de la fuente simbólica. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Devuelve o establece la información de la fuente simbólica. Null significa que la fuente es indefinida y debe heredarse del Master. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Devuelve o establece el texto en superíndice o subíndice. Valor de -100 % (subíndice) a 100 % (superíndice). **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Devuelve:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Devuelve o establece el texto en superíndice o subíndice. Valor de -100 % (subíndice) a 100 % (superíndice). **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Devuelve o establece el tamaño de fuente mínimo, para el cual se debe activar el kerning. **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Devuelve:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Devuelve o establece el tamaño de fuente mínimo, para el cual se debe activar el kerning. **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Devuelve o establece el Id de un idioma de corrección. Se usa para la verificación ortográfica y gramatical. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Devuelve o establece el Id de un idioma de corrección. Se usa para la verificación ortográfica y gramatical. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Devuelve o establece el Id de un idioma alternativo. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Devuelve o establece el Id de un idioma alternativo. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Devuelve o establece el incremento del espaciado entre caracteres. **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Devuelve:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Devuelve o establece el incremento del espaciado entre caracteres. **Float.NaN** significa que el valor es indefinido y debe heredarse del Master. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, la corrección ortográfica está permitida. El valor predeterminado es false.

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
public abstract void setSpellCheck(boolean value)
```

Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, la corrección ortográfica está permitida. El valor predeterminado es false.

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