---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Esta clase contiene las propiedades de formato de la porción de texto.
type: docs
url: /es/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Esta clase contiene las propiedades de formato de la porción de texto. A diferencia de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), todas las propiedades de esta clase son modificables.

--------------------

Esta clase se usa para obtener y manipular las propiedades de formato de texto definidas para la porción concreta. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan “indefinido”.

Para obtener los valores de parámetros de formato efectivos, incluidos los heredados, debe usar el método [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) que devuelve una instancia [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).  

## Métodos

| Método | Descripción |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Returns the LineFormat properties for text outlining. |
| [getFillFormat()](#getFillFormat--) | Returns the text FillFormat properties. |
| [getEffectFormat()](#getEffectFormat--) | Returns the text EffectFormat properties. |
| [getHighlightColor()](#getHighlightColor--) | Returns the color used to highlight a text. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Returns the LineFormat properties used to outline underline line. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Returns the underline line FillFormat properties. |
| [getFontBold()](#getFontBold--) | Determines whether the font is bold. |
| [setFontBold(byte value)](#setFontBold-byte-) | Determines whether the font is bold. |
| [getFontItalic()](#getFontItalic--) | Determines whether the font is itallic. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Determines whether the font is itallic. |
| [getKumimoji()](#getKumimoji--) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determines whether the height of a text should be normalized. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Determines whether the height of a text should be normalized. |
| [getProofDisabled()](#getProofDisabled--) | Determines whether the text shouldn't be proofed. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Determines whether the text shouldn't be proofed. |
| [getFontUnderline()](#getFontUnderline--) | Returns or sets the text underline type. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Returns or sets the text underline type. |
| [getTextCapType()](#getTextCapType--) | Returns or sets the type of text capitalization. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Returns or sets the type of text capitalization. |
| [getStrikethroughType()](#getStrikethroughType--) | Returns or sets the strikethrough type of a text. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Returns or sets the strikethrough type of a text. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [getFontHeight()](#getFontHeight--) | Returns or sets the font height of a portion. |
| [setFontHeight(float value)](#setFontHeight-float-) | Returns or sets the font height of a portion. |
| [getLatinFont()](#getLatinFont--) | Returns or sets the Latin font info. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returns or sets the Latin font info. |
| [getEastAsianFont()](#getEastAsianFont--) | Returns or sets the East Asian font info. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returns or sets the East Asian font info. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returns or sets the complex script font info. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returns or sets the complex script font info. |
| [getSymbolFont()](#getSymbolFont--) | Returns or sets the symbolic font info. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Returns or sets the symbolic font info. |
| [getEscapement()](#getEscapement--) | Returns or sets the superscript or subscript text. |
| [setEscapement(float value)](#setEscapement-float-) | Returns or sets the superscript or subscript text. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returns or sets the minimal font size, for which kerning should be switched on. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Returns or sets the minimal font size, for which kerning should be switched on. |
| [getLanguageId()](#getLanguageId--) | Returns or sets the Id of a proofing language. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Returns or sets the Id of a proofing language. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Returns or sets the Id of an alternative language. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Returns or sets the Id of an alternative language. |
| [getSpacing()](#getSpacing--) | Returns or sets the intercharacter spacing increment. |
| [setSpacing(float value)](#setSpacing-float-) | Returns or sets the intercharacter spacing increment. |
| [getSpellCheck()](#getSpellCheck--) | Gets or sets a value indicating whether spell checking is enabled for the text portion. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Gets or sets a value indicating whether spell checking is enabled for the text portion. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Devuelve las propiedades LineFormat para el contorno del texto. No se aplica herencia. **Solo lectura** [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Devuelve las propiedades FillFormat del texto. No se aplica herencia. **Solo lectura** [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Devuelve las propiedades EffectFormat del texto. No se aplica herencia. **Solo lectura** [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Devuelve:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Devuelve el color usado para resaltar un texto. No se aplica herencia. **Solo lectura** [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Devuelve las propiedades LineFormat usadas para delinear la línea subrayada. No se aplica herencia. **Solo lectura** [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Devuelve las propiedades FillFormat de la línea subrayada. No se aplica herencia. **Solo lectura** [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Determina si la fuente es negrita. No se aplica herencia. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Determina si la fuente es negrita. No se aplica herencia. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Determina si la fuente es itallic. No se aplica herencia. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Determina si la fuente es itallic. No se aplica herencia. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Determina si los números deben ignorar la disposición vertical del texto específica de lenguas orientales. No se aplica herencia. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Determina si los números deben ignorar la disposición vertical del texto específica de lenguas orientales. No se aplica herencia. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Determina si la altura de un texto debe normalizarse. No se aplica herencia. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Determina si la altura de un texto debe normalizarse. No se aplica herencia. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Determina si el texto no debe revisarse. No se aplica herencia. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Determina si el texto no debe revisarse. No se aplica herencia. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. **Lectura/Escritura** [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Devuelve:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. **Lectura/Escritura** [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Devuelve o establece el tipo de capitalización del texto. No se aplica herencia. **Lectura/Escritura** [TextCapType](../../com.aspose.slides/textcaptype).

**Devuelve:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Devuelve o establece el tipo de capitalización del texto. No se aplica herencia. **Lectura/Escritura** [TextCapType](../../com.aspose.slides/textcaptype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Devuelve o establece el tipo de tachado de un texto. No se aplica herencia. **Lectura/Escritura** [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Devuelve:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Devuelve o establece el tipo de tachado de un texto. No se aplica herencia. **Lectura/Escritura** [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. **Lectura/Escritura** [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Devuelve o establece la altura de la fuente de una porción. **Float.NaN** indica que la altura es indefinida y debe heredarse del Master. **Lectura/Escritura** float.

**Devuelve:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Devuelve o establece la altura de la fuente de una porción. **Float.NaN** indica que la altura es indefinida y debe heredarse del Master. **Lectura/Escritura** float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Devuelve o establece la información de la fuente Latin. Null indica que la fuente es indefinida y debe heredarse del Master. **Lectura/Escritura** [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Devuelve o establece la información de la fuente Latin. Null indica que la fuente es indefinida y debe heredarse del Master. **Lectura/Escritura** [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Devuelve o establece la información de la fuente East Asian. Null indica que la fuente es indefinida y debe heredarse del Master. **Lectura/Escritura** [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Devuelve o establece la información de la fuente East Asian. Null indica que la fuente es indefinida y debe heredarse del Master. **Lectura/Escritura** [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Devuelve o establece la información de la fuente de scripts complejos. Null indica que la fuente es indefinida y debe heredarse del Master. **Lectura/Escritura** [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Devuelve o establece la información de la fuente de scripts complejos. Null indica que la fuente es indefinida y debe heredarse del Master. **Lectura/Escritura** [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Devuelve o establece la información de la fuente simbólica. Null indica que la fuente es indefinida y debe heredarse del Master. **Lectura/Escritura** [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Devuelve o establece la información de la fuente simbólica. Null indica que la fuente es indefinida y debe heredarse del Master. **Lectura/Escritura** [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Devuelve o establece el texto superíndice o subíndice. Valor de -100 % (subíndice) a 100 % (superíndice). **Float.NaN** indica que el valor es indefinido y debe heredarse del Master. **Lectura/Escritura** float.

**Devuelve:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Devuelve o establece el texto superíndice o subíndice. Valor de -100 % (subíndice) a 100 % (superíndice). **Float.NaN** indica que el valor es indefinido y debe heredarse del Master. **Lectura/Escritura** float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Devuelve o establece el tamaño de fuente mínimo para el que debe activarse el kerning. **Float.NaN** indica que el valor es indefinido y debe heredarse del Master. **Lectura/Escritura** float.

**Devuelve:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Devuelve o establece el tamaño de fuente mínimo para el que debe activarse el kerning. **Float.NaN** indica que el valor es indefinido y debe heredarse del Master. **Lectura/Escritura** float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Devuelve o establece el Id de un idioma de revisión. Usado para la comprobación ortográfica y gramatical. **Lectura/Escritura** String.

**Devuelve:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Devuelve o establece el Id de un idioma de revisión. Usado para la comprobación ortográfica y gramatical. **Lectura/Escritura** String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Devuelve o establece el Id de un idioma alternativo. **Lectura/Escritura** String.

**Devuelve:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Devuelve o establece el Id de un idioma alternativo. **Lectura/Escritura** String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Devuelve o establece el incremento de espaciado entre caracteres. **Float.NaN** indica que el valor es indefinido y debe heredarse del Master. **Lectura/Escritura** float.

**Devuelve:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Devuelve o establece el incremento de espaciado entre caracteres. **Float.NaN** indica que el valor es indefinido y debe heredarse del Master. **Lectura/Escritura** float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las comprobaciones ortográficas para los elementos de texto. Cuando se establece en true, la corrección ortográfica está permitida. El valor predeterminado es false.

--------------------

> ```
> El siguiente ejemplo muestra cómo habilitar la bandera SpellCheck antes de guardar la presentación:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Acceda a la primera porción de texto dentro de la primera forma en la primera diapositiva
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Habilite la corrección ortográfica para esta porción de texto
>      portion.getPortionFormat().setSpellCheck(true);
>      // Guarde la presentación modificada
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

Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las comprobaciones ortográficas para los elementos de texto. Cuando se establece en true, la corrección ortográfica está permitida. El valor predeterminado es false.

--------------------

> ```
> El siguiente ejemplo muestra cómo habilitar la bandera SpellCheck antes de guardar la presentación:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Acceda a la primera porción de texto dentro de la primera forma en la primera diapositiva
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Habilite la corrección ortográfica para esta porción de texto
>      portion.getPortionFormat().setSpellCheck(true);
>      // Guarde la presentación modificada
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |