---
title: IMathBorderBox
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Rysuje prostokątną lub inną ramkę wokół IMathElement.
type: docs
url: /pl/com.aspose.slides/imathborderbox/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Rysuje prostokątną lub inną ramkę wokół IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getHideTop()](#getHideTop--) | Ukryj górną krawędź (default is false) - określa ukryty lub widoczny stan górnej krawędzi ramki. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Ukryj górną krawędź (default is false) - określa ukryty lub widoczny stan górnej krawędzi ramki. |
| [getHideBottom()](#getHideBottom--) | Ukryj dolną krawędź (default is false) - określa ukryty lub widoczny stan dolnej krawędzi ramki. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Ukryj dolną krawędź (default is false) - określa ukryty lub widoczny stan dolnej krawędzi ramki. |
| [getHideLeft()](#getHideLeft--) | Ukryj lewą krawędź (default is false) - określa ukryty lub widoczny stan lewej krawędzi ramki. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Ukryj lewą krawędź (default is false) - określa ukryty lub widoczny stan lewej krawędzi ramki. |
| [getHideRight()](#getHideRight--) | Ukryj prawą krawędź (default is false) - określa ukryty lub widoczny stan prawej krawędzi ramki. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Ukryj prawą krawędź (default is false) - określa ukryty lub widoczny stan prawej krawędzi ramki. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Przekreślenie poziome (default is false) - określa ukryty lub widoczny stan poziomej linii przekreślenia. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Przekreślenie poziome (default is false) - określa ukryty lub widoczny stan poziomej linii przekreślenia. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Przekreślenie pionowe (default is false) - określa ukryty lub widoczny stan pionowej linii przekreślenia. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Przekreślenie pionowe (default is false) - określa ukryty lub widoczny stan pionowej linii przekreślenia. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Przekreślenie od dolnego lewego do górnego prawego (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Przekreślenie od dolnego lewego do górnego prawego (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Przekreślenie od górnego lewego do dolnego prawego (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Przekreślenie od górnego lewego do dolnego prawego (default is false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument bazowy

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

Ukryj górną krawędź (default is false) - określa ukryty lub widoczny stan górnej krawędzi ramki.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Zwraca:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

Ukryj górną krawędź (default is false) - określa ukryty lub widoczny stan górnej krawędzi ramki.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

Ukryj dolną krawędź (default is false) - określa ukryty lub widoczny stan dolnej krawędzi ramki.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Zwraca:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

Ukryj dolną krawędź (default is false) - określa ukryty lub widoczny stan dolnej krawędzi ramki.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

Ukryj lewą krawędź (default is false) - określa ukryty lub widoczny stan lewej krawędzi ramki.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Zwraca:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

Ukryj lewą krawędź (default is false) - określa ukryty lub widoczny stan lewej krawędzi ramki.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

Ukryj prawą krawędź (default is false) - określa ukryty lub widoczny stan prawej krawędzi ramki.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Zwraca:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

Ukryj prawą krawędź (default is false) - określa ukryty lub widoczny stan prawej krawędzi ramki.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

Przekreślenie poziome (default is false) - określa ukryty lub widoczny stan poziomej linii przekreślenia.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Zwraca:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

Przekreślenie poziome (default is false) - określa ukryty lub widoczny stan poziomej linii przekreślenia.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

Przekreślenie pionowe (default is false) - określa ukryty lub widoczny stan pionowej linii przekreślenia.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Zwraca:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

Przekreślenie pionowe (default is false) - określa ukryty lub widoczny stan pionowej linii przekreślenia.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Przekreślenie od dolnego lewego do górnego prawego (default is false). Określa ukryty lub widoczny stan przekreślenia przekątnej od dolnego lewego rogu do górnego prawego rogu ramki.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Zwraca:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

Przekreślenie od dolnego lewego do górnego prawego (default is false). Określa ukryty lub widoczny stan przekreślenia przekątnej od dolnego lewego rogu do górnego prawego rogu ramki.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Przekreślenie od górnego lewego do dolnego prawego (default is false). Określa ukryty lub widoczny stan przekreślenia przekątnej od górnego lewego rogu do dolnego prawego rogu ramki.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Zwraca:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

Przekreślenie od górnego lewego do dolnego prawego (default is false). Określa ukryty lub widoczny stan przekreślenia przekątnej od górnego lewego rogu do dolnego prawego rogu ramki.

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |