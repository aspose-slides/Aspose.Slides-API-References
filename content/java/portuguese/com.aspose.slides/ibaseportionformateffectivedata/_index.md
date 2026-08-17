---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Base interface for immutable objects which contain effective text portion formatting properties.
type: docs
url: /pt/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Interface base para objetos imutáveis que contêm propriedades de formatação de porção de texto efetivas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Retorna as propriedades LineFormat para contorno de texto. |
| [getFillFormat()](#getFillFormat--) | Retorna as propriedades FillFormat do texto. |
| [getEffectFormat()](#getEffectFormat--) | Retorna as propriedades EffectFormat do texto. |
| [getHighlightColor()](#getHighlightColor--) | Retorna a cor usada para realçar um texto. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Retorna as propriedades LineFormat usadas para contornar a linha de sublinhado. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Retorna as propriedades FillFormat da linha de sublinhado. |
| [getFontBold()](#getFontBold--) | Determina se a fonte está em negrito. |
| [getFontItalic()](#getFontItalic--) | Determina se a fonte está em itálico. |
| [getKumimoji()](#getKumimoji--) | Determina se os números devem ignorar o layout de texto vertical específico de idioma oriental. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determina se a altura de um texto deve ser normalizada. |
| [getProofDisabled()](#getProofDisabled--) | Determina se o texto não deve ser revisado. |
| [getFontUnderline()](#getFontUnderline--) | Retorna o tipo de sublinhado do texto. |
| [getTextCapType()](#getTextCapType--) | Retorna o tipo de capitalização do texto. |
| [getStrikethroughType()](#getStrikethroughType--) | Retorna o tipo de tachado de um texto. |
| [getSmartTagClean()](#getSmartTagClean--) | Determina se a smart tag deve ser limpa. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determina se o estilo de sublinhado tem propriedades LineFormat próprias ou as herda das propriedades LineFormat do texto. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determina se o estilo de sublinhado tem propriedades FillFormat próprias ou as herda das propriedades FillFormat do texto. |
| [getFontHeight()](#getFontHeight--) | Retorna a altura da fonte da porção de texto, em pontos. |
| [getLatinFont()](#getLatinFont--) | Retorna as informações da fonte Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Retorna as informações da fonte East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Retorna as informações da fonte complex script. |
| [getSymbolFont()](#getSymbolFont--) | Retorna as informações da fonte simbólica. |
| [getEscapement()](#getEscapement--) | Retorna o texto sobrescrito ou subscrito. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Retorna o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. |
| [getLanguageId()](#getLanguageId--) | Retorna o Id de um idioma. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Retorna o Id de um idioma alternativo. |
| [getSpacing()](#getSpacing--) | Retorna o incremento de espaçamento intercaracteres, em pontos. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Retorna as propriedades LineFormat para contorno de texto. Somente leitura [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Retorna:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Retorna as propriedades FillFormat do texto. Somente leitura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Retorna:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Retorna as propriedades EffectFormat do texto. Somente leitura [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Retorna:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```


Retorna a cor usada para realçar um texto. Somente leitura java.awt.Color.

**Retorna:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Retorna as propriedades LineFormat usadas para contornar a linha de sublinhado. Somente leitura [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Retorna:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Retorna as propriedades FillFormat da linha de sublinhado. Somente leitura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Retorna:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


Determina se a fonte está em negrito. Somente leitura boolean.

**Retorna:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


Determina se a fonte está em itálico. Somente leitura boolean.

**Retorna:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


Determina se os números devem ignorar o layout de texto vertical específico de idioma oriental. Somente leitura boolean.

**Retorna:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Determina se a altura de um texto deve ser normalizada. Somente leitura boolean.

**Retorna:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Determina se o texto não deve ser revisado. Somente leitura boolean.

**Retorna:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Retorna o tipo de sublinhado do texto. Somente leitura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Retorna:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Retorna o tipo de capitalização do texto. Somente leitura [TextCapType](../../com.aspose.slides/textcaptype).

**Retorna:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Retorna o tipo de tachado de um texto. Somente leitura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Retorna:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Determina se a smart tag deve ser limpa. Somente leitura boolean.

**Retorna:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


Determina se o estilo de sublinhado tem propriedades LineFormat próprias ou as herda das propriedades LineFormat do texto. Somente leitura boolean.

**Retorna:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Determina se o estilo de sublinhado tem propriedades FillFormat próprias ou as herda das propriedades FillFormat do texto. Somente leitura boolean.

**Retorna:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Retorna a altura da fonte da porção de texto, em pontos. Somente leitura float.

**Retorna:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Retorna as informações da fonte Latin. Somente leitura [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Retorna as informações da fonte East Asian. Somente leitura [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Retorna as informações da fonte complex script. Somente leitura [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Retorna as informações da fonte simbólica. Somente leitura [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Retorna o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). Somente leitura float.

**Retorna:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Retorna o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. Somente leitura float.

**Retorna:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Retorna o Id de um idioma. Somente leitura String.

**Retorna:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Retorna o Id de um idioma alternativo. Somente leitura String.

**Retorna:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Retorna o incremento de espaçamento intercaracteres, em pontos. Somente leitura float.

**Retorna:**
float