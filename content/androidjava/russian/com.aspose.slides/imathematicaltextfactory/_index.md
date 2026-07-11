---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /ru/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Позволяет создавать элемент MathematicalText

Для совместимости с COM

## Методы

| Метод | Описание |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Создать пустой элемент MathematicalText |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Создать элемент MathematicalText с указанным значением |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Создать пустой элемент MathematicalText с указанным значением |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Создать пустой элемент MathematicalText с указанным значением и свойствами форматирования |

### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Создать пустой элемент MathematicalText

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - новый Mathematical Text

### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Создать элемент MathematicalText с указанным значением

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathSymbol | char | одиночный символ, используемый в качестве текстового значения |

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - новый Mathematical Text

### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Создать пустой элемент MathematicalText с указанным значением

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | текстовое значение |

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - новый Mathematical Text

### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Создать пустой элемент MathematicalText с указанным значением и свойствами форматирования

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | текстовое значение |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | настройки формата текста |

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - новый Mathematical Text