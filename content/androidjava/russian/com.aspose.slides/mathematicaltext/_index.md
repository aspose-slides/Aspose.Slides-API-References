---
title: MathematicalText
second_title: Aspose.Slides для Android через справочник API Java
description: Математический текст
type: docs
url: /ru/com.aspose.slides/mathematicaltext/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Математический текст

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Конструктор по умолчанию (создать String.Empty Value) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Создать MathText с одним символом |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Создать MathematicalText из текста |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Создать MathematicalText из текста и настроек формата |
## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Текстовое значение |
| [setValue(String value)](#setValue-java.lang.String-) | Текстовое значение |
| [getFormat()](#getFormat--) | Свойства форматирования текста |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Конструктор по умолчанию (создать String.Empty Value)

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText();
> ```

### MathematicalText(char mathSymbol) {#MathematicalText-char-}
```
public MathematicalText(char mathSymbol)
```


Создать MathText с одним символом

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathSymbol | char | один символ |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Создать MathematicalText из текста

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | значение текста |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Создать MathematicalText из текста и настроек формата

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | значение текста |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | настройки формата текста |

### getValue() {#getValue--}
```
public final String getValue()
```


Текстовое значение

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Возвращаемое значение:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Текстовое значение

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Свойства форматирования текста

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Возвращаемое значение:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Получить дочерние элементы

**Возвращаемое значение:**
com.aspose.slides.IMathElement[]