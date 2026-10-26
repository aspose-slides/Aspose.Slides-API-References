---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java Справочник API
description: Базовый интерфейс для неизменяемых объектов, содержащих эффективные свойства форматирования текстовых фрагментов.
type: docs
url: /ru/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Базовый интерфейс для неизменяемых объектов, содержащих эффективные свойства форматирования текстовых фрагментов.
## Методы

| Метод | Описание |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Возвращает свойства LineFormat для обводки текста. |
| [getFillFormat()](#getFillFormat--) | Возвращает свойства FillFormat текста. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает свойства EffectFormat текста. |
| [getHighlightColor()](#getHighlightColor--) | Возвращает цвет, используемый для выделения текста. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Возвращает свойства LineFormat, используемые для обводки подчеркивающей линии. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Возвращает свойства FillFormat подчеркивающей линии. |
| [getFontBold()](#getFontBold--) | Определяет, является ли шрифт полужирным. |
| [getFontItalic()](#getFontItalic--) | Определяет, является ли шрифт курсивным. |
| [getKumimoji()](#getKumimoji--) | Определяет, должны ли цифры игнорировать вертикальное размещение текста, специфичное для восточных языков. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Определяет, следует ли нормализовать высоту текста. |
| [getProofDisabled()](#getProofDisabled--) | Определяет, не требуется ли проверка текста. |
| [getFontUnderline()](#getFontUnderline--) | Возвращает тип подчеркивания текста. |
| [getTextCapType()](#getTextCapType--) | Возвращает тип капитализации текста. |
| [getStrikethroughType()](#getStrikethroughType--) | Возвращает тип зачеркивания текста. |
| [getSmartTagClean()](#getSmartTagClean--) | Определяет, следует ли очищать смарт-тег. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от свойств LineFormat текста. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от свойств FillFormat текста. |
| [getFontHeight()](#getFontHeight--) | Возвращает высоту шрифта текстового фрагмента в пунктах. |
| [getLatinFont()](#getLatinFont--) | Возвращает информацию о латиноамериканском шрифте. |
| [getEastAsianFont()](#getEastAsianFont--) | Возвращает информацию о восточноазиатском шрифте. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Возвращает информацию о шрифте сложных сценариев. |
| [getSymbolFont()](#getSymbolFont--) | Возвращает информацию о символьном шрифте. |
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

**Возвращаемое значение:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Возвращает свойства FillFormat текста. Только для чтения [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Возвращаемое значение:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Возвращает свойства EffectFormat текста. Только для чтения [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Возвращаемое значение:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

Возвращает цвет, используемый для выделения текста. Только для чтения java.awt.Color.

**Возвращаемое значение:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Возвращает свойства LineFormat, используемые для обводки подчеркивающей линии. Только для чтения [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Возвращаемое значение:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Возвращает свойства FillFormat подчеркивающей линии. Только для чтения [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Возвращаемое значение:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Определяет, является ли шрифт полужирным. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Определяет, является ли шрифт курсивным. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Определяет, должны ли цифры игнорировать вертикальное размещение текста, специфичное для восточных языков. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Определяет, следует ли нормализовать высоту текста. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Определяет, не требуется ли проверка текста. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Возвращает тип подчеркивания текста. Только для чтения [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Возвращаемое значение:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Возвращает тип капитализации текста. Только для чтения [TextCapType](../../com.aspose.slides/textcaptype).

**Возвращаемое значение:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Возвращает тип зачеркивания текста. Только для чтения [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Возвращаемое значение:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Определяет, следует ли очищать смарт-тег. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от свойств LineFormat текста. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от свойств FillFormat текста. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Возвращает высоту шрифта текстового фрагмента в пунктах. Только для чтения float.

**Возвращаемое значение:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Возвращает информацию о латиноамериканском шрифте. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Возвращает информацию о восточноазиатском шрифте. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Возвращает информацию о шрифте сложных сценариев. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Возвращает информацию о символьном шрифте. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Возвращает надстрочный или подстрочный текст. Значение от -100 % (подстрочный) до 100 % (надстрочный). Только для чтения float.

**Возвращаемое значение:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Возвращает минимальный размер шрифта, при котором включается кернинг. Только для чтения float.

**Возвращаемое значение:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Возвращает идентификатор языка. Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Возвращает идентификатор альтернативного языка. Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Возвращает приращение межсимвольного интервала в пунктах. Только для чтения float.

**Возвращаемое значение:**
float