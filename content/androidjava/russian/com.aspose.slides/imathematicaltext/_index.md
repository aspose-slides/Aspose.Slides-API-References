---
title: IMathematicalText
second_title: Aspose.Slides для Android через справочник Java API
description: Математический текст
type: docs
url: /ru/com.aspose.slides/imathematicaltext/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Математический текст

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Текстовое значение |
| [setValue(String value)](#setValue-java.lang.String-) | Текстовое значение |
| [getFormat()](#getFormat--) | Свойства форматирования текста |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
public abstract IPortionFormat getFormat()
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