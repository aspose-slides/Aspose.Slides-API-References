---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Interfaz base para objetos inmutables que contienen propiedades de formato de porción de texto efectivas.
type: docs
url: /es/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Interfaz base para objetos inmutables que contienen propiedades de formato de porción de texto efectivas.

## Métodos

| Método | Descripción |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Devuelve las propiedades LineFormat para el contorno del texto. |
| [getFillFormat()](#getFillFormat--) | Devuelve las propiedades FillFormat del texto. |
| [getEffectFormat()](#getEffectFormat--) | Devuelve las propiedades EffectFormat del texto. |
| [getHighlightColor()](#getHighlightColor--) | Devuelve el color usado para resaltar un texto. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Devuelve las propiedades LineFormat usadas para delinear la línea de subrayado. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Devuelve las propiedades FillFormat de la línea de subrayado. |
| [getFontBold()](#getFontBold--) | Determina si la fuente es negrita. |
| [getFontItalic()](#getFontItalic--) | Determina si la fuente es cursiva. |
| [getKumimoji()](#getKumimoji--) | Determina si los números deben ignorar la disposición vertical del texto específica de lenguas orientales. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determina si la altura de un texto debe normalizarse. |
| [getProofDisabled()](#getProofDisabled--) | Determina si el texto no debe revisarse ortográficamente. |
| [getFontUnderline()](#getFontUnderline--) | Devuelve el tipo de subrayado del texto. |
| [getTextCapType()](#getTextCapType--) | Devuelve el tipo de capitalización del texto. |
| [getStrikethroughType()](#getStrikethroughType--) | Devuelve el tipo de tachado del texto. |
| [getSmartTagClean()](#getSmartTagClean--) | Determina si la etiqueta inteligente debe limpiarse. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. |
| [getFontHeight()](#getFontHeight--) | Devuelve la altura de fuente de la porción de texto, en puntos. |
| [getLatinFont()](#getLatinFont--) | Devuelve la información de la fuente Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Devuelve la información de la fuente East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Devuelve la información de la fuente de script complejo. |
| [getSymbolFont()](#getSymbolFont--) | Devuelve la información de la fuente simbólica. |
| [getEscapement()](#getEscapement--) | Devuelve el texto en superíndice o subíndice. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Devuelve el tamaño mínimo de fuente para el que se debe activar el kerning. |
| [getLanguageId()](#getLanguageId--) | Devuelve el Id de un idioma. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Devuelve el Id de un idioma alternativo. |
| [getSpacing()](#getSpacing--) | Devuelve el incremento de espaciado intercarácter, en puntos. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

Devuelve las propiedades LineFormat para el contorno del texto. Solo lectura [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Devuelve:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Devuelve las propiedades FillFormat del texto. Solo lectura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Devuelve:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Devuelve las propiedades EffectFormat del texto. Solo lectura [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Devuelve:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

Devuelve el color usado para resaltar un texto. Solo lectura java.awt.Color.

**Devuelve:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Devuelve las propiedades LineFormat usadas para delinear la línea de subrayado. Solo lectura [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Devuelve:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Devuelve las propiedades FillFormat de la línea de subrayado. Solo lectura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Devuelve:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Determina si la fuente es negrita. Solo lectura boolean.

**Devuelve:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Determina si la fuente es cursiva. Solo lectura boolean.

**Devuelve:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Determina si los números deben ignorar la disposición vertical del texto específica de lenguas orientales. Solo lectura boolean.

**Devuelve:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Determina si la altura de un texto debe normalizarse. Solo lectura boolean.

**Devuelve:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Determina si el texto no debe revisarse ortográficamente. Solo lectura boolean.

**Devuelve:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Devuelve el tipo de subrayado del texto. Solo lectura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Devuelve:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Devuelve el tipo de capitalización del texto. Solo lectura [TextCapType](../../com.aspose.slides/textcaptype).

**Devuelve:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Devuelve el tipo de tachado del texto. Solo lectura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Devuelve:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Determina si la etiqueta inteligente debe limpiarse. Solo lectura boolean.

**Devuelve:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. Solo lectura boolean.

**Devuelve:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. Solo lectura boolean.

**Devuelve:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Devuelve la altura de fuente de la porción de texto, en puntos. Solo lectura float.

**Devuelve:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Devuelve la información de la fuente Latin. Solo lectura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Devuelve la información de la fuente East Asian. Solo lectura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Devuelve la información de la fuente de script complejo. Solo lectura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Devuelve la información de la fuente simbólica. Solo lectura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Devuelve el texto en superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice). Solo lectura float.

**Devuelve:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Devuelve el tamaño mínimo de fuente para el que se debe activar el kerning. Solo lectura float.

**Devuelve:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Devuelve el Id de un idioma. Solo lectura String.

**Devuelve:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Devuelve el Id de un idioma alternativo. Solo lectura String.

**Devuelve:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Devuelve el incremento de espaciado intercarácter, en puntos. Solo lectura float.

**Devuelve:**
float