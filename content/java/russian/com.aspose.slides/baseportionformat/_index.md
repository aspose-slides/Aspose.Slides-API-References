---
title: BasePortionFormat
second_title: Aspose.Slides для Java — справочник API
description: Общие свойства форматирования части текста.
type: docs
url: /ru/com.aspose.slides/baseportionformat/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Общие свойства форматирования части текста.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Возвращает свойства LineFormat для обведения текста. |
| [getFillFormat()](#getFillFormat--) | Возвращает свойства FillFormat текста. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает свойства EffectFormat текста. |
| [getHighlightColor()](#getHighlightColor--) | Возвращает цвет, используемый для выделения текста. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Возвращает свойства LineFormat, используемые для обведения линии подчёркивания. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Возвращает свойства FillFormat линии подчёркивания. |
| [getFontBold()](#getFontBold--) | Определяет, является ли шрифт полужирным. |
| [setFontBold(byte value)](#setFontBold-byte-) | Определяет, является ли шрифт полужирным. |
| [getFontItalic()](#getFontItalic--) | Определяет, является ли шрифт курсивным. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Определяет, является ли шрифт курсивным. |
| [getKumimoji()](#getKumimoji--) | Определяет, должны ли цифры игнорировать восточноязычный специфичный вертикальный макет текста. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Определяет, должны ли цифры игнорировать восточноязычный специфичный вертикальный макет текста. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Определяет, должна ли высота текста быть нормализована. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Определяет, должна ли высота текста быть нормализована. |
| [getProofDisabled()](#getProofDisabled--) | Определяет, не следует ли проверять текст. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Определяет, не следует ли проверять текст. |
| [getFontUnderline()](#getFontUnderline--) | Возвращает или задает тип подчёркивания текста. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Возвращает или задает тип подчёркивания текста. |
| [getTextCapType()](#getTextCapType--) | Возвращает или задает тип капитализации текста. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Возвращает или задает тип капитализации текста. |
| [getStrikethroughType()](#getStrikethroughType--) | Возвращает или задает тип перечёркивания текста. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Возвращает или задает тип перечёркивания текста. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Определяет, имеет ли стиль подчёркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Определяет, имеет ли стиль подчёркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Определяет, имеет ли стиль подчёркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Определяет, имеет ли стиль подчёркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. |
| [getFontHeight()](#getFontHeight--) | Возвращает или задает высоту шрифта части. |
| [setFontHeight(float value)](#setFontHeight-float-) | Возвращает или задает высоту шрифта части. |
| [getLatinFont()](#getLatinFont--) | Возвращает или задает информацию о латинском шрифте. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Возвращает или задает информацию о латинском шрифте. |
| [getEastAsianFont()](#getEastAsianFont--) | Возвращает или задает информацию о восточноазиатском шрифте. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Возвращает или задает информацию о восточноазиатском шрифте. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Возвращает или задает информацию о шрифте для сложных скриптов. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Возвращает или задает информацию о шрифте для сложных скриптов. |
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

Версия. Только для чтения long.

**Возвращает:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Возвращает свойства LineFormat для обведения текста. Наследования не применяется. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Возвращает свойства FillFormat текста. Наследования не применяется. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращает:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Возвращает свойства EffectFormat текста. Наследования не применяется. Только для чтения [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Возвращает:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Возвращает цвет, используемый для выделения текста. Наследования не применяется. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Возвращает свойства LineFormat, используемые для обведения линии подчёркивания. Наследования не применяется. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Возвращает свойства FillFormat линии подчёркивания. Наследования не применяется. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращает:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Определяет, является ли шрифт полужирным. Наследования не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Определяет, является ли шрифт полужирным. Наследования не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Определяет, является ли шрифт курсивным. Наследования не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Определяет, является ли шрифт курсивным. Наследования не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Определяет, должны ли цифры игнорировать восточноязычный специфичный вертикальный макет текста. Наследования не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Определяет, должны ли цифры игнорировать восточноязычный специфичный вертикальный макет текста. Наследования не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Определяет, должна ли высота текста быть нормализована. Наследования не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Определяет, должна ли высота текста быть нормализована. Наследования не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Определяет, не следует ли проверять текст. Наследования не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Определяет, не следует ли проверять текст. Наследования не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Возвращает или задает тип подчёркивания текста. Наследования не применяется. Чтение/запись [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Возвращает:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Возвращает или задает тип подчёркивания текста. Наследования не применяется. Чтение/запись [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Возвращает или задает тип капитализации текста. Наследования не применяется. Чтение/запись [TextCapType](../../com.aspose.slides/textcaptype).

**Возвращает:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Возвращает или задает тип капитализации текста. Наследования не применяется. Чтение/запись [TextCapType](../../com.aspose.slides/textcaptype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Возвращает или задает тип перечёркивания текста. Наследования не применяется. Чтение/запись [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Возвращает:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Возвращает или задает тип перечёркивания текста. Наследования не применяется. Чтение/запись [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Определяет, имеет ли стиль подчёркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Определяет, имеет ли стиль подчёркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Определяет, имеет ли стиль подчёркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Определяет, имеет ли стиль подчёркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Возвращает или задает высоту шрифта части. **Float.NaN** означает, что высота не определена и должна наследоваться от Master. Чтение/запись  float .

**Возвращает:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Возвращает или задает высоту шрифта части. **Float.NaN** означает, что высота не определена и должна наследоваться от Master. Чтение/запись  float .

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

Возвращает или задает информацию о восточноазиатском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Возвращает или задает информацию о восточноазиатском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Возвращает или задает информацию о шрифте для сложных скриптов. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Возвращает или задает информацию о шрифте для сложных скриптов. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

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

Получает или задает значение, указывающее, включена ли проверка орфографии для части текста. Когда значение равно false, проверка орфографии для элементов текста подавляется. Когда true, проверка включена. Значение по умолчанию — false.

**Возвращает:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Получает или задает значение, указывающее, включена ли проверка орфографии для части текста. Когда значение равно false, проверка орфографии для элементов текста подавляется. Когда true, проверка включена. Значение по умолчанию — false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Получить первый фрагмент текста внутри первой формы на первом слайде
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Включить проверку орфографии для этого фрагмента текста
>      portion.getPortionFormat().setSpellCheck(true);
>      // Сохранить изменённую презентацию
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
boolean

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Получить первый фрагмент текста внутри первой формы на первом слайде
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Включить проверку орфографии для этого фрагмента текста
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