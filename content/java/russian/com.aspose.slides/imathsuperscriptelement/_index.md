---
title: IMathSuperscriptElement
second_title: Справочник API Aspose.Slides для Java
description: Определяет объект надстрочного индекса, который состоит из основания и уменьшенного надстрочного индекса, расположенного выше и справа
type: docs
url: /ru/com.aspose.slides/imathsuperscriptelement/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Определяет объект надстрочного индекса, который состоит из основания и уменьшенного надстрочного индекса, расположенного выше и справа

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
```
## Методы

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getSuperscript()](#getSuperscript--) | Надстрочный |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Базовый аргумент

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Надстрочный

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)