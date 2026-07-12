---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the text portion formatting properties.
type: docs
url: /pt/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Esta classe contém as propriedades de formatação da porção de texto. Ao contrário de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), todas as propriedades desta classe são graváveis.

--------------------

Esta classe é usada para retornar e manipular as propriedades de formatação da porção de texto definidas para a porção específica. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores que significam "indefinido".

Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) que retorna uma instância [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Métodos

| Método | Descrição |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Retorna as propriedades LineFormat para contorno de texto. |
| [getFillFormat()](#getFillFormat--) | Retorna as propriedades FillFormat do texto. |
| [getEffectFormat()](#getEffectFormat--) | Retorna as propriedades EffectFormat do texto. |
| [getHighlightColor()](#getHighlightColor--) | Retorna a cor usada para destacar um texto. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Retorna as propriedades LineFormat usadas para contornar a linha de sublinhado. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Retorna as propriedades FillFormat da linha de sublinhado. |
| [getFontBold()](#getFontBold--) | Determina se a fonte está em negrito. |
| [setFontBold(byte value)](#setFontBold-byte-) | Determina se a fonte está em negrito. |
| [getFontItalic()](#getFontItalic--) | Determina se a fonte está em itálico. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Determina se a fonte está em itálico. |
| [getKumimoji()](#getKumimoji--) | Determina se os números devem ignorar o layout vertical de texto específico de línguas orientais. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Determina se os números devem ignorar o layout vertical de texto específico de línguas orientais. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determina se a altura de um texto deve ser normalizada. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Determina se a altura de um texto deve ser normalizada. |
| [getProofDisabled()](#getProofDisabled--) | Determina se o texto não deve ser revisado. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Determina se o texto não deve ser revisado. |
| [getFontUnderline()](#getFontUnderline--) | Retorna ou define o tipo de sublinhado do texto. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Retorna ou define o tipo de sublinhado do texto. |
| [getTextCapType()](#getTextCapType--) | Retorna ou define o tipo de capitalização do texto. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Retorna ou define o tipo de capitalização do texto. |
| [getStrikethroughType()](#getStrikethroughType--) | Retorna ou define o tipo de tachado de um texto. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Retorna ou define o tipo de tachado de um texto. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determina se o estilo de sublinhado possui propriedades LineFormat próprias ou as herda das propriedades LineFormat do texto. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Determina se o estilo de sublinhado possui propriedades LineFormat próprias ou as herda das propriedades LineFormat do texto. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determina se o estilo de sublinhado possui propriedades FillFormat próprias ou as herda das propriedades FillFormat do texto. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Determina se o estilo de sublinhado possui propriedades FillFormat próprias ou as herda das propriedades FillFormat do texto. |
| [getFontHeight()](#getFontHeight--) | Retorna ou define a altura da fonte de uma porção. |
| [setFontHeight(float value)](#setFontHeight-float-) | Retorna ou define a altura da fonte de uma porção. |
| [getLatinFont()](#getLatinFont--) | Retorna ou define as informações da fonte latina. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Retorna ou define as informações da fonte latina. |
| [getEastAsianFont()](#getEastAsianFont--) | Retorna ou define as informações da fonte do Leste Asiático. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Retorna ou define as informações da fonte do Leste Asiático. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Retorna ou define as informações da fonte de script complexo. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Retorna ou define as informações da fonte de script complexo. |
| [getSymbolFont()](#getSymbolFont--) | Retorna ou define as informações da fonte simbólica. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Retorna ou define as informações da fonte simbólica. |
| [getEscapement()](#getEscapement--) | Retorna ou define o texto sobrescrito ou subscrito. |
| [setEscapement(float value)](#setEscapement-float-) | Retorna ou define o texto sobrescrito ou subscrito. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. |
| [getLanguageId()](#getLanguageId--) | Retorna ou define o Id de um idioma de revisão. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Retorna ou define o Id de um idioma de revisão. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Retorna ou define o Id de um idioma alternativo. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Retorna ou define o Id de um idioma alternativo. |
| [getSpacing()](#getSpacing--) | Retorna ou define o incremento de espaçamento entre caracteres. |
| [setSpacing(float value)](#setSpacing-float-) | Retorna ou define o incremento de espaçamento entre caracteres. |
| [getSpellCheck()](#getSpellCheck--) | Obtém ou define um valor que indica se a verificação ortográfica está habilitada para a porção de texto. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Obtém ou define um valor que indica se a verificação ortográfica está habilitada para a porção de texto. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Retorna as propriedades LineFormat para contorno de texto. Nenhuma herança aplicada. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Retorna as propriedades FillFormat do texto. Nenhuma herança aplicada. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Retorna as propriedades EffectFormat do texto. Nenhuma herança aplicada. Somente leitura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retorna:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Retorna a cor usada para destacar um texto. Nenhuma herança aplicada. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Retorna as propriedades LineFormat usadas para contornar a linha de sublinhado. Nenhuma herança aplicada. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Retorna as propriedades FillFormat da linha de sublinhado. Nenhuma herança aplicada. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Determina se a fonte está em negrito. Nenhuma herança aplicada. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Determina se a fonte está em negrito. Nenhuma herança aplicada. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Determina se a fonte está em itálico. Nenhuma herança aplicada. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Determina se a fonte está em itálico. Nenhuma herança aplicada. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Determina se os números devem ignorar o layout vertical de texto específico de línguas orientais. Nenhuma herança aplicada. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Determina se os números devem ignorar o layout vertical de texto específico de línguas orientais. Nenhuma herança aplicada. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Determina se a altura de um texto deve ser normalizada. Nenhuma herança aplicada. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Determina se a altura de um texto deve ser normalizada. Nenhuma herança aplicada. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Determina se o texto não deve ser revisado. Nenhuma herança aplicada. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Determina se o texto não deve ser revisado. Nenhuma herança aplicada. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Retorna ou define o tipo de sublinhado do texto. Nenhuma herança aplicada. Leitura/Gravação [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Retorna:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Retorna ou define o tipo de sublinhado do texto. Nenhuma herança aplicada. Leitura/Gravação [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Retorna ou define o tipo de capitalização do texto. Nenhuma herança aplicada. Leitura/Gravação [TextCapType](../../com.aspose.slides/textcaptype).

**Retorna:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Retorna ou define o tipo de capitalização do texto. Nenhuma herança aplicada. Leitura/Gravação [TextCapType](../../com.aspose.slides/textcaptype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Retorna ou define o tipo de tachado de um texto. Nenhuma herança aplicada. Leitura/Gravação [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Retorna:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Retorna ou define o tipo de tachado de um texto. Nenhuma herança aplicada. Leitura/Gravação [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Determina se o estilo de sublinhado possui propriedades LineFormat próprias ou as herda das propriedades LineFormat do texto. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Determina se o estilo de sublinhado possui propriedades LineFormat próprias ou as herda das propriedades LineFormat do texto. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Determina se o estilo de sublinhado possui propriedades FillFormat próprias ou as herda das propriedades FillFormat do texto. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Determina se o estilo de sublinhado possui propriedades FillFormat próprias ou as herda das propriedades FillFormat do texto. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Retorna ou define a altura da fonte de uma porção. **Float.NaN** significa que a altura está indefinida e deve ser herdada do Mestre. Leitura/Gravação float.

**Retorna:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Retorna ou define a altura da fonte de uma porção. **Float.NaN** significa que a altura está indefinida e deve ser herdada do Mestre. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Retorna ou define as informações da fonte latina. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Retorna ou define as informações da fonte latina. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [IFontData](../../com.aspose.slides/ifontdata).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Retorna ou define as informações da fonte do Leste Asiático. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Retorna ou define as informações da fonte do Leste Asiático. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [IFontData](../../com.aspose.slides/ifontdata).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Retorna ou define as informações da fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Retorna ou define as informações da fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [IFontData](../../com.aspose.slides/ifontdata).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Retorna ou define as informações da fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Retorna ou define as informações da fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [IFontData](../../com.aspose.slides/ifontdata).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Retorna ou define o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **Float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação float.

**Retorna:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Retorna ou define o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **Float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **Float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação float.

**Retorna:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **Float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Retorna ou define o Id de um idioma de revisão. Usado para verificação ortográfica e gramatical. Leitura/Gravação String.

**Retorna:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Retorna ou define o Id de um idioma de revisão. Usado para verificação ortográfica e gramatical. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Retorna ou define o Id de um idioma alternativo. Leitura/Gravação String.

**Retorna:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Retorna ou define o Id de um idioma alternativo. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Retorna ou define o incremento de espaçamento entre caracteres. **Float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação float.

**Retorna:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Retorna ou define o incremento de espaçamento entre caracteres. **Float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Obtém ou define um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Acesse a primeira porção de texto dentro da primeira forma no primeiro slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Habilite a verificação ortográfica para esta porção de texto
>      portion.getPortionFormat().setSpellCheck(true);
>      // Salve a apresentação modificada
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Obtém ou define um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Acesse a primeira porção de texto dentro da primeira forma no primeiro slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Habilite a verificação ortográfica para esta porção de texto
>      portion.getPortionFormat().setSpellCheck(true);
>      // Salve a apresentação modificada
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |