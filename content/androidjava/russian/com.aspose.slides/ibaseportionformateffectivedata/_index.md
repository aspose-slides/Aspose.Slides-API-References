---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides для Android через Java API Reference
description: Базовый интерфейс для неизменяемых объектов, содержащих свойства эффективного форматирования текстовых фрагментов.
type: docs
url: /ru/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Базовый интерфейс для неизменяемых объектов, содержащих свойства эффективного форматирования текстовых фрагментов.
## Методы

| Метод | Описание |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Возвращает свойства LineFormat для обводки текста. |
| [getFillFormat()](#getFillFormat--) | Возвращает свойства FillFormat текста. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает свойства EffectFormat текста. |
| [getHighlightColor()](#getHighlightColor--) | Возвращает цвет, использующийся для выделения текста. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Возвращает свойства LineFormat, используемые для обводки линии подчёркивания. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Возвращает свойства FillFormat линии подчёркивания. |
| [getFontBold()](#getFontBold--) | Определяет, является ли шрифт полужирным. |
| [getFontItalic()](#getFontItalic--) | Определяет, является ли шрифт курсивным. |
| [getKumimoji()](#getKumimoji--) | Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную раскладку текста. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Определяет, следует ли нормализовать высоту текста. |
| [getProofDisabled()](#getProofDisabled--) | Определяет, не следует ли проверять текст. |
| [getFontUnderline()](#getFontUnderline--) | Возвращает тип подчёркивания текста. |
| [getTextCapType()](#getTextCapType--) | Возвращает тип капитализации текста. |
| [getStrikethroughType()](#getStrikethroughType--) | Возвращает тип зачеркивания текста. |
| [getSmartTagClean()](#getSmartTagClean--) | Определяет, следует ли очистить смарт-тег. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Определяет, имеет ли стиль подчёркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Определяет, имеет ли стиль подчёркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. |
| [getFontHeight()](#getFontHeight--) | Возвращает высоту шрифта текстового фрагмента в пунктах. |
| [getLatinFont()](#getLatinFont--) | Возвращает информацию о латинском шрифте. |
| [getEastAsianFont()](#getEastAsianFont--) | Возвращает информацию о восточно-азиатском шрифте. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Возвращает информацию о шрифте сложного написания. |
| [getSymbolFont()](#getSymbolFont--) | Возвращает информацию о символическом шрифте. |
| [getEscapement()](#getEscapement--) | Возвращает надстрочный или подстрочный текст. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Возвращает минимальный размер шрифта, при котором включается кернинг. |
| [getLanguageId()](#getLanguageId--) | Возвращает идентификатор языка. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Возвращает идентификатор альтернативного языка. |
| [getSpacing()](#getSpacing--) | Возвращает приращение межсимвольного интервала в пунктах. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Возвращает свойства LineFormat для обводки текста. Только для чтения [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Возвращает:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Возвращает свойства FillFormat текста. Только для чтения [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Возвращает:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Возвращает свойства EffectFormat текста. Только для чтения [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Возвращает:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```


Возвращает цвет, использующийся для выделения текста. Только для чтения java.lang.Integer.

**Возвращает:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Возвращает свойства LineFormat, используемые для обводки линии подчёркивания. Только для чтения [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Возвращает:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Возвращает свойства FillFormat линии подчёркивания. Только для чтения [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Возвращает:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


Определяет, является ли шрифт полужирным. Только для чтения boolean.

**Возвращает:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


Определяет, является ли шрифт курсивным. Только для чтения boolean.

**Возвращает:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную раскладку текста. Только для чтения boolean.

**Возвращает:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Определяет, следует ли нормализовать высоту текста. Только для чтения boolean.

**Возвращает:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Определяет, не следует ли проверять текст. Только для чтения boolean.

**Возвращает:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Возвращает тип подчёркивания текста. Только для чтения [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Возвращает:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Возвращает тип капитализации текста. Только для чтения [TextCapType](../../com.aspose.slides/textcaptype).

**Возвращает:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Возвращает тип зачеркивания текста. Только для чтения [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Возвращает:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Определяет, следует ли очистить смарт-тег. Только для чтения boolean.

**Возвращает:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


Определяет, имеет ли стиль подчёркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. Только для чтения boolean.

**Возвращает:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Определяет, имеет ли стиль подчёркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. Только для чтения boolean.

**Возвращает:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Возвращает высоту шрифта текстового фрагмента в пунктах. Только для чтения float.

**Возвращает:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Возвращает информацию о латинском шрифте. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Возвращает информацию о восточно-азиатском шрифте. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Возвращает информацию о шрифте сложного написания. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Возвращает информацию о символическом шрифте. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Возвращает надстрочный или подстрочный текст. Значение от -100% (подстрочный) до 100% (надстрочный). Только для чтения float.

**Возвращает:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Возвращает минимальный размер шрифта, при котором включается кернинг. Только для чтения float.

**Возвращает:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Возвращает идентификатор языка. Только для чтения String.

**Возвращает:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Возвращает идентификатор альтернативного языка. Только для чтения String.

**Возвращает:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Возвращает приращение межсимвольного интервала в пунктах. Только для чтения float.

**Возвращает:**
float