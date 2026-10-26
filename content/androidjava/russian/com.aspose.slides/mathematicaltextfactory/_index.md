---
title: MathematicalTextFactory
second_title: Aspose.Slides для Android через справочник Java API
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
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


Создать пустой элемент MathematicalText

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - новый Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


Создать элемент MathematicalText с указанным значением

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathSymbol | char | один символ, используемый в качестве текстового значения |

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - новый Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
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
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Создать пустой элемент MathematicalText с указанным значением и свойствами форматирования

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | текстовое значение |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | настройки формата текста |

**Возвращаемое значение:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - новый Mathematical Text