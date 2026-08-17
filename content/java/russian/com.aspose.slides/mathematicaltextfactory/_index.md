---
title: MathematicalTextFactory
second_title: Справочник API Aspose.Slides для Java
description: Позволяет создавать элемент MathematicalText
type: docs
url: /ru/com.aspose.slides/mathematicaltextfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

Позволяет создавать элемент MathematicalText

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Создать пустой элемент математического текста |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Создать элемент математического текста с указанным значением |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Создать пустой элемент математического текста с указанным значением |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Создать пустой элемент математического текста с указанным значением и свойствами форматирования |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```

Создать пустой элемент математического текста

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

Создать элемент математического текста с указанным значением

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathSymbol | char | один символ, используемый в качестве текстового значения |

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

Создать пустой элемент математического текста с указанным значением

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | текстовое значение |

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Создать пустой элемент математического текста с указанным значением и свойствами форматирования

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | текстовое значение |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | настройки формата текста |

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text