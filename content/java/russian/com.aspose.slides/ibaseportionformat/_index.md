---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the text portion formatting properties.
type: docs
url: /ru/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Этот класс содержит свойства форматирования текстовых фрагментов. В отличие от [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), все свойства этого класса доступны для записи.

--------------------

Этот класс используется для получения и изменения свойств форматирования текстовых фрагментов, определённых для конкретного фрагмента. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить фактические значения параметров форматирования, включая унаследованные, необходимо использовать метод [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective), который возвращает экземпляр [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Методы

| Метод | Описание |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Возвращает свойства LineFormat для обводки текста. |
| [getFillFormat()](#getFillFormat--) | Возвращает свойства FillFormat текста. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает свойства EffectFormat текста. |
| [getHighlightColor()](#getHighlightColor--) | Возвращает цвет, используемый для выделения текста. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Возвращает свойства LineFormat, используемые для обводки подчеркивающей линии. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Возвращает свойства FillFormat подчеркивающей линии. |
| [getFontBold()](#getFontBold--) | Определяет, жирный ли шрифт. |
| [setFontBold(byte value)](#setFontBold-byte-) | Определяет, жирный ли шрифт. |
| [getFontItalic()](#getFontItalic--) | Определяет, курсивен ли шрифт. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Определяет, курсивен ли шрифт. |
| [getKumimoji()](#getKumimoji--) | Определяет, должны ли цифры игнорировать специфическую для восточных языков вертикальную раскладку текста. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Определяет, должны ли цифры игнорировать специфическую для восточных языков вертикальную раскладку текста. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Определяет, должна ли высота текста быть нормализована. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Определяет, должна ли высота текста быть нормализована. |
| [getProofDisabled()](#getProofDisabled--) | Определяет, не следует ли проверять текст. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Определяет, не следует ли проверять текст. |
| [getFontUnderline()](#getFontUnderline--) | Возвращает или задаёт тип подчеркивания текста. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Возвращает или задаёт тип подчеркивания текста. |
| [getTextCapType()](#getTextCapType--) | Возвращает или задаёт тип капитализации текста. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Возвращает или задаёт тип капитализации текста. |
| [getStrikethroughType()](#getStrikethroughType--) | Возвращает или задаёт тип зачеркивания текста. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Возвращает или задаёт тип зачеркивания текста. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. |
| [getFontHeight()](#getFontHeight--) | Возвращает или задаёт высоту шрифта фрагмента. |
| [setFontHeight(float value)](#setFontHeight-float-) | Возвращает или задаёт высоту шрифта фрагмента. |
| [getLatinFont()](#getLatinFont--) | Возвращает или задаёт информацию о латинском шрифте. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Возвращает или задаёт информацию о латинском шрифте. |
| [getEastAsianFont()](#getEastAsianFont--) | Возвращает или задаёт информацию о восточноазиатском шрифте. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Возвращает или задаёт информацию о восточноазиатском шрифте. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Возвращает или задаёт информацию о шрифте сложных скриптов. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Возвращает или задаёт информацию о шрифте сложных скриптов. |
| [getSymbolFont()](#getSymbolFont--) | Возвращает или задаёт информацию о символическом шрифте. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Возвращает или задаёт информацию о символическом шрифте. |
| [getEscapement()](#getEscapement--) | Возвращает или задаёт надстрочный или подстрочный текст. |
| [setEscapement(float value)](#setEscapement-float-) | Возвращает или задаёт надстрочный или подстрочный текст. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Возвращает или задаёт минимальный размер шрифта, при котором следует включать кернинг. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Возвращает или задаёт минимальный размер шрифта, при котором следует включать кернинг. |
| [getLanguageId()](#getLanguageId--) | Возвращает или задаёт идентификатор языка проверки. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Возвращает или задаёт идентификатор языка проверки. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Возвращает или задаёт идентификатор альтернативного языка. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Возвращает или задаёт идентификатор альтернативного языка. |
| [getSpacing()](#getSpacing--) | Возвращает или задаёт приращение межсимвольного интервала. |
| [setSpacing(float value)](#setSpacing-float-) | Возвращает или задаёт приращение межсимвольного интервала. |
| [getSpellCheck()](#getSpellCheck--) | Получает или задаёт значение, указывающее, включена ли проверка орфографии для текстового фрагмента. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Получает или задаёт значение, указывающее, включена ли проверка орфографии для текстового фрагмента. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Возвращает свойства LineFormat для обводки текста. Наследование не применяется. Только чтение [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращаемое значение:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Возвращает свойства FillFormat текста. Наследование не применяется. Только чтение [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Возвращает свойства EffectFormat текста. Наследование не применяется. Только чтение [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Возвращаемое значение:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только чтение [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Возвращает свойства LineFormat, используемые для обводки подчеркивающей линии. Наследование не применяется. Только чтение [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращаемое значение:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Возвращает свойства FillFormat подчеркивающей линии. Наследование не применяется. Только чтение [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Определяет, жирный ли шрифт. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Определяет, жирный ли шрифт. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Определяет, курсивен ли шрифт. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Определяет, курсивен ли шрифт. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Определяет, должны ли цифры игнорировать специфическую для восточных языков вертикальную раскладку текста. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimojibyte value)
```

Определяет, должны ли цифры игнорировать специфическую для восточных языков вертикальную раскладку текста. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Определяет, не следует ли проверять текст. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Определяет, не следует ли проверять текст. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Возвращает или задаёт тип подчеркивания текста. Наследование не применяется. Чтение/запись [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Возвращаемое значение:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Возвращает или задаёт тип подчеркивания текста. Наследование не применяется. Чтение/запись [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Возвращает или задаёт тип капитализации текста. Наследование не применяется. Чтение/запись [TextCapType](../../com.aspose.slides/textcaptype).

**Возвращаемое значение:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Возвращает или задаёт тип капитализации текста. Наследование не применяется. Чтение/запись [TextCapType](../../com.aspose.slides/textcaptype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Возвращает или задаёт тип зачеркивания текста. Наследование не применяется. Чтение/запись [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Возвращаемое значение:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Возвращает или задаёт тип зачеркивания текста. Наследование не применяется. Чтение/запись [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Возвращает или задаёт высоту шрифта фрагмента. **Float.NaN** означает, что высота неопределена и должна быть унаследована от мастера. Чтение/запись float.

**Возвращаемое значение:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Возвращает или задаёт высоту шрифта фрагмента. **Float.NaN** означает, что высота неопределена и должна быть унаследована от мастера. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Возвращает или задаёт информацию о латинском шрифте. Null означает, что шрифт неопределён и должен быть унаследован от мастера. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Возвращает или задаёт информацию о латинском шрифте. Null означает, что шрифт неопределён и должен быть унаследован от мастера. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Возвращает или задаёт информацию о восточноазиатском шрифте. Null означает, что шрифт неопределён и должен быть унаследован от мастера. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Возвращает или задаёт информацию о восточноазиатском шрифте. Null означает, что шрифт неопределён и должен быть унаследован от мастера. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Возвращает или задаёт информацию о шрифте сложных скриптов. Null означает, что шрифт неопределён и должен быть унаследован от мастера. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Возвращает или задаёт информацию о шрифте сложных скриптов. Null означает, что шрифт неопределён и должен быть унаследован от мастера. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Возвращает или задаёт информацию о символическом шрифте. Null означает, что шрифт неопределён и должен быть унаследован от мастера. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Возвращает или задаёт информацию о символическом шрифте. Null означает, что шрифт неопределён и должен быть унаследован от мастера. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Возвращает или задаёт надстрочный или подстрочный текст. Значение от -100 % (подстрочный) до 100 % (надстрочный). **Float.NaN** означает, что значение неопределено и должно быть унаследовано от мастера. Чтение/запись float.

**Возвращаемое значение:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Возвращает или задаёт надстрочный или подстрочный текст. Значение от -100 % (подстрочный) до 100 % (надстрочный). **Float.NaN** означает, что значение неопределено и должно быть унаследовано от мастера. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Возвращает или задаёт минимальный размер шрифта, при котором следует включать кернинг. **Float.NaN** означает, что значение неопределено и должно быть унаследовано от мастера. Чтение/запись float.

**Возвращаемое значение:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Возвращает или задаёт минимальный размер шрифта, при котором следует включать кернинг. **Float.NaN** означает, что значение неопределено и должно быть унаследовано от мастера. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Возвращает или задаёт идентификатор языка проверки. Используется для проверки орфографии и грамматики. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Возвращает или задаёт идентификатор языка проверки. Используется для проверки орфографии и грамматики. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Возвращает или задаёт идентификатор альтернативного языка. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Возвращает или задаёт идентификатор альтернативного языка. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Возвращает или задаёт приращение межсимвольного интервала. **Float.NaN** означает, что значение неопределено и должно быть унаследовано от мастера. Чтение/запись float.

**Возвращаемое значение:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Возвращает или задаёт приращение межсимвольного интервала. **Float.NaN** означает, что значение неопределено и должно быть унаследовано от мастера. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Получает или задаёт значение, указывающее, включена ли проверка орфографии для текстового фрагмента. Когда установлено false, проверка орфографии для текстовых элементов подавляется. При true проверка включена. Значение по умолчанию — false.

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

**Возвращаемое значение:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Получает или задаёт значение, указывающее, включена ли проверка орфографии для текстового фрагмента. Когда установлено false, проверка орфографии для текстовых элементов подавляется. При true проверка включена. Значение по умолчанию — false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
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