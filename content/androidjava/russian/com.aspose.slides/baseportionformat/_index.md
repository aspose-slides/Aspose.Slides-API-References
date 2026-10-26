---
title: BasePortionFormat
second_title: Aspose.Slides для Android через Java API Справка
description: Общие свойства форматирования части текста.
type: docs
url: /ru/com.aspose.slides/baseportionformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Общие свойства форматирования части текста.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Возвращает свойства LineFormat для обводки текста. |
| [getFillFormat()](#getFillFormat--) | Возвращает свойства FillFormat текста. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает свойства EffectFormat текста. |
| [getHighlightColor()](#getHighlightColor--) | Возвращает цвет, используемый для выделения текста. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Возвращает свойства LineFormat, используемые для обводки линии подчеркивания. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Возвращает свойства FillFormat линии подчеркивания. |
| [getFontBold()](#getFontBold--) | Определяет, является ли шрифт полужирным. |
| [setFontBold(byte value)](#setFontBold-byte-) | Определяет, является ли шрифт полужирным. |
| [getFontItalic()](#getFontItalic--) | Определяет, является ли шрифт курсивным. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Определяет, является ли шрифт курсивным. |
| [getKumimoji()](#getKumimoji--) | Определяет, следует ли игнорировать числа при восточноязычном вертикальном расположении текста. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Определяет, следует ли игнорировать числа при восточноязычном вертикальном расположении текста. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Определяет, следует ли нормализовать высоту текста. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Определяет, следует ли нормализовать высоту текста. |
| [getProofDisabled()](#getProofDisabled--) | Определяет, следует ли отключать проверку текста. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Определяет, следует ли отключать проверку текста. |
| [getFontUnderline()](#getFontUnderline--) | Возвращает или задает тип подчеркивания текста. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Возвращает или задает тип подчеркивания текста. |
| [getTextCapType()](#getTextCapType--) | Возвращает или задает тип капитализации текста. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Возвращает или задает тип капитализации текста. |
| [getStrikethroughType()](#getStrikethroughType--) | Возвращает или задает тип зачёркивания текста. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Возвращает или задает тип зачёркивания текста. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от LineFormat текста. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от LineFormat текста. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от FillFormat текста. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от FillFormat текста. |
| [getFontHeight()](#getFontHeight--) | Возвращает или задает высоту шрифта части текста. |
| [setFontHeight(float value)](#setFontHeight-float-) | Возвращает или задает высоту шрифта части текста. |
| [getLatinFont()](#getLatinFont--) | Возвращает или задает информацию о латинском шрифте. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Возвращает или задает информацию о латинском шрифте. |
| [getEastAsianFont()](#getEastAsianFont--) | Возвращает или задает информацию о шрифте Восточной Азии. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Возвращает или задает информацию о шрифте Восточной Азии. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Возвращает или задает информацию о шрифте сложных сценариев. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Возвращает или задает информацию о шрифте сложных сценариев. |
| [getSymbolFont()](#getSymbolFont--) | Возвращает или задает информацию о символическом шрифте. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Возвращает или задает информацию о символическом шрифте. |
| [getEscapement()](#getEscapement--) | Возвращает или задает надстрочный или подстрочный текст. |
| [setEscapement(float value)](#setEscapement-float-) | Возвращает или задает надстрочный или подстрочный текст. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Возвращает или задает минимальный размер шрифта, при котором включается кернинг. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Возвращает или задает минимальный размер шрифта, при котором включается кернинг. |
| [getLanguageId()](#getLanguageId--) | Возвращает или задает идентификатор языка проверки. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Возвращает или задает идентификатор языка проверки. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Возвращает или задает идентификатор альтернативного языка. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Возвращает или задает идентификатор альтернативного языка. |
| [getSpacing()](#getSpacing--) | Возвращает или задает приращение межсимвольного интервала. |
| [setSpacing(float value)](#setSpacing-float-) | Возвращает или задает приращение межсимвольного интервала. |
| [getSpellCheck()](#getSpellCheck--) | Получает или задает значение, указывающее, включена ли проверка орфографии для части текста. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Получает или задает значение, указывающее, включена ли проверка орфографии для части текста. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Версия. Только для чтения, тип long.

**Возвращает:**
long
### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```


Возвращает свойства LineFormat для обводки текста. Наследование не применяется. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Возвращает свойства FillFormat текста. Наследование не применяется. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращает:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


Возвращает свойства EffectFormat текста. Наследование не применяется. Только для чтения [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Возвращает:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```


Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```


Возвращает свойства LineFormat, используемые для обводки линии подчеркивания. Наследование не применяется. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```


Возвращает свойства FillFormat линии подчеркивания. Наследование не применяется. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращает:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```


Определяет, является ли шрифт полужирным. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```


Определяет, является ли шрифт полужирным. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```


Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```


Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```


Определяет, следует ли игнорировать числа при восточноязычном вертикальном расположении текста. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```


Определяет, следует ли игнорировать числа при восточноязычном вертикальном расположении текста. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```


Определяет, следует ли нормализовать высоту текста. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```


Определяет, следует ли нормализовать высоту текста. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```


Определяет, следует ли отключать проверку текста. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```


Определяет, следует ли отключать проверку текста. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```


Возвращает или задает тип подчеркивания текста. Наследование не применяется. Чтение/запись [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Возвращает:**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```


Возвращает или задает тип подчеркивания текста. Наследование не применяется. Чтение/запись [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```


Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись [TextCapType](../../com.aspose.slides/textcaptype).

**Возвращает:**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```


Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись [TextCapType](../../com.aspose.slides/textcaptype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```


Возвращает или задает тип зачёркивания текста. Наследование не применяется. Чтение/запись [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Возвращает:**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```


Возвращает или задает тип зачёркивания текста. Наследование не применяется. Чтение/запись [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```


Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от LineFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```


Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от LineFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```


Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от FillFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```


Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от FillFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```


Возвращает или задает высоту шрифта части текста. **Float.NaN** означает, что высота не определена и должна наследоваться от Master. Чтение/запись  float .

**Возвращает:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```


Возвращает или задает высоту шрифта части текста. **Float.NaN** означает, что высота не определена и должна наследоваться от Master. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```


Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```


Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```


Возвращает или задает информацию о шрифте Восточной Азии. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```


Возвращает или задает информацию о шрифте Восточной Азии. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```


Возвращает или задает информацию о шрифте сложных сценариев. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```


Возвращает или задает информацию о шрифте сложных сценариев. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```


Возвращает или задает информацию о символическом шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```


Возвращает или задает информацию о символическом шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```


Возвращает или задает надстрочный или подстрочный текст. Значение от -100 % (подстрочный) до 100 % (надстрочный). **Float.NaN** означает, что значение не определено и должно наследоваться от Master. Чтение/запись  float .

**Возвращает:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```


Возвращает или задает надстрочный или подстрочный текст. Значение от -100 % (подстрочный) до 100 % (надстрочный). **Float.NaN** означает, что значение не определено и должно наследоваться от Master. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```


Возвращает или задает минимальный размер шрифта, при котором включается кернинг. **Float.NaN** означает, что значение не определено и должно наследоваться от Master. Чтение/запись  float .

**Возвращает:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```


Возвращает или задает минимальный размер шрифта, при котором включается кернинг. **Float.NaN** означает, что значение не определено и должно наследоваться от Master. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```


Возвращает или задает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Чтение/запись String.

**Возвращает:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```


Возвращает или задает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```


Возвращает или задает идентификатор альтернативного языка. Чтение/запись String.

**Возвращает:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```


Возвращает или задает идентификатор альтернативного языка. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```


Возвращает или задает приращение межсимвольного интервала. **Float.NaN** означает, что значение не определено и должно наследоваться от Master. Чтение/запись  float .

**Возвращает:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```


Возвращает или задает приращение межсимвольного интервала. **Float.NaN** означает, что значение не определено и должно наследоваться от Master. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```


Получает или задает значение, указывающее, включена ли проверка орфографии для части текста. Когда это свойство имеет значение false, проверка орфографии для текстовых элементов подавляется. Когда установлено true, проверка орфографии разрешена. Значение по умолчанию — false.

--------------------

> ```
> Следующий пример демонстрирует включение флага SpellCheck перед сохранением презентации:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Доступ к первой части текста внутри первой формы на первом слайде
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Включить проверку орфографии для этой части текста
>      portion.getPortionFormat().setSpellCheck(true);
>      // Сохранить изменённую презентацию
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```


Получает или задает значение, указывающее, включена ли проверка орфографии для части текста. Когда это свойство имеет значение false, проверка орфографии для текстовых элементов подавляется. Когда установлено true, проверка орфографии разрешена. Значение по умолчанию — false.

--------------------

> ```
> Следующий пример демонстрирует включение флага SpellCheck перед сохранением презентации:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Доступ к первой части текста внутри первой формы на первом слайде
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Включить проверку орфографии для этой части текста
>      portion.getPortionFormat().setSpellCheck(true);
>      // Сохранить изменённую презентацию
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |