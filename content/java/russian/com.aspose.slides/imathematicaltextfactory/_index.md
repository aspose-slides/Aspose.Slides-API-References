---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java справочник API
description: Позволяет создавать элемент MathematicalText
type: docs
url: /ru/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Позволяет создавать элемент MathematicalText

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Создает пустой элемент математического текста

**Возвращает:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Создает элемент математического текста с указанным значением

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathSymbol | char | один символ, используемый в качестве значения текста |

**Возвращает:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Создает пустой элемент математического текста с указанным значением

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | значение текста |

**Возвращает:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Создает пустой элемент математического текста с указанным значением и свойствами форматирования

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | значение текста |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | настройки формата текста |

**Возвращает:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text