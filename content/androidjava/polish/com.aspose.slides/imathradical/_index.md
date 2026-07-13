---
title: IMathRadical
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Określa funkcję pierwiastkową składającą się z podstawy i opcjonalnego stopnia.
type: docs
url: /pl/com.aspose.slides/imathradical/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Określa funkcję pierwiastkową, składającą się z podstawy i opcjonalnego stopnia. Przykładem obiektu pierwiastka jest \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // pierwiastek sześcienny
```
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument podstawy |
| [getDegree()](#getDegree--) | Argument stopnia |
| [getHideDegree()](#getHideDegree--) | Ukryj stopień. Gdy jest true, stopień nie jest wyświetlany, tak jak w \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Ukryj stopień. Gdy jest true, stopień nie jest wyświetlany, tak jak w \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument podstawy

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // pierwiastek sześcienny
>  IMathElement baseElem = radical.getBase();
>  ```


**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Argument stopnia

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // pierwiastek sześcienny
>  IMathElement degreeElem = radical.getDegree();
>  ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Ukryj stopień. Gdy jest true, stopień nie jest wyświetlany, tak jak w \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // pierwiastek sześcienny
>  radical.setHideDegree(true);
>  ```

**Zwraca:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Ukryj stopień. Gdy jest true, stopień nie jest wyświetlany, tak jak w \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // pierwiastek sześcienny
>  radical.setHideDegree(true);
>  ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |