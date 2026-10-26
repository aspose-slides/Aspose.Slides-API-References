---
title: MathBorderBox
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Rysuje prostokątną lub inną ramkę wokół IMathElement.
type: docs
url: /pl/com.aspose.slides/mathborderbox/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Rysuje prostokątną lub inną ramkę wokół IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Tworzy element MathBorderBox z prostokątną ramką |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Tworzy element MathBorderBox |
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getHideTop()](#getHideTop--) | Ukryj górną krawędź (wartość domyślna to false) – określa, czy górna krawędź ramki jest ukryta czy widoczna. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Ukryj górną krawędź (wartość domyślna to false) – określa, czy górna krawędź ramki jest ukryta czy widoczna. |
| [getHideBottom()](#getHideBottom--) | Ukryj dolną krawędź (wartość domyślna to false) – określa, czy dolna krawędź ramki jest ukryta czy widoczna. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Ukryj dolną krawędź (wartość domyślna to false) – określa, czy dolna krawędź ramki jest ukryta czy widoczna. |
| [getHideLeft()](#getHideLeft--) | Ukryj lewą krawędź (wartość domyślna to false) – określa, czy lewa krawędź ramki jest ukryta czy widoczna. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Ukryj lewą krawędź (wartość domyślna to false) – określa, czy lewa krawędź ramki jest ukryta czy widoczna. |
| [getHideRight()](#getHideRight--) | Ukryj prawą krawędź (wartość domyślna to false) – określa, czy prawa krawędź ramki jest ukryta czy widoczna. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Ukryj prawą krawędź (wartość domyślna to false) – określa, czy prawa krawędź ramki jest ukryta czy widoczna. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Przekreślenie poziome (wartość domyślna to false) – określa, czy pozioma linia przekreślenia jest ukryta czy widoczna. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Przekreślenie poziome (wartość domyślna to false) – określa, czy pozioma linia przekreślenia jest ukryta czy widoczna. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Przekreślenie pionowe (wartość domyślna to false) – określa, czy pionowa linia przekreślenia jest ukryta czy widoczna. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Przekreślenie pionowe (wartość domyślna to false) – określa, czy pionowa linia przekreślenia jest ukryta czy widoczna. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Przekreślenie od lewego dolnego do prawego górnego (wartość domyślna to false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Przekreślenie od lewego dolnego do prawego górnego (wartość domyślna to false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Przekreślenie od lewego górnego do prawego dolnego (wartość domyślna to false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Przekreślenie od lewego górnego do prawego dolnego (wartość domyślna to false). |
| [getChildren()](#getChildren--) | Pobierz elementy potomne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaków kontrolnych |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Tworzy element MathBorderBox z prostokątną ramką

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Podstawowy element, do którego zastosowano ramkę. Może być nullem. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Tworzy element MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Podstawowy element, do którego zastosowano ramkę |
| hideTop | boolean | Ukryj górną krawędź |
| hideBottom | boolean | Ukryj dolną krawędź |
| hideLeft | boolean | Ukryj lewą krawędź |
| hideRight | boolean | Ukryj prawą krawędź |
| strikethroughHorizontal | boolean | Przekreślenie poziome |
| strikethroughVertical | boolean | Przekreślenie pionowe |
| strikethroughBottomLeftToTopRight | boolean | Przekreślenie od lewego dolnego do prawego górnego |
| strikethroughTopLeftToBottomRight | boolean | Przekreślenie od lewego górnego do prawego dolnego |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argument bazowy

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Ukryj górną krawędź (wartość domyślna to false) – określa, czy górna krawędź ramki jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Zwraca:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Ukryj górną krawędź (wartość domyślna to false) – określa, czy górna krawędź ramki jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Ukryj dolną krawędź (wartość domyślna to false) – określa, czy dolna krawędź ramki jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Zwraca:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Ukryj dolną krawędź (wartość domyślna to false) – określa, czy dolna krawędź ramki jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Ukryj lewą krawędź (wartość domyślna to false) – określa, czy lewa krawędź ramki jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Zwraca:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Ukryj lewą krawędź (wartość domyślna to false) – określa, czy lewa krawędź ramki jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Ukryj prawą krawędź (wartość domyślna to false) – określa, czy prawa krawędź ramki jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Zwraca:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Ukryj prawą krawędź (wartość domyślna to false) – określa, czy prawa krawędź ramki jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Przekreślenie poziome (wartość domyślna to false) – określa, czy pozioma linia przekreślenia jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Zwraca:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Przekreślenie poziome (wartość domyślna to false) – określa, czy pozioma linia przekreślenia jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Przekreślenie pionowe (wartość domyślna to false) – określa, czy pionowa linia przekreślenia jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Zwraca:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Przekreślenie pionowe (wartość domyślna to false) – określa, czy pionowa linia przekreślenia jest ukryta czy widoczna.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Przekreślenie od lewego dolnego do prawego górnego (wartość domyślna to false). Określa, czy przekreślenie przekątnej od lewego dolnego do prawego górnego jest ukryte czy widoczne.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Zwraca:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Przekreślenie od lewego dolnego do prawego górnego (wartość domyślna to false). Określa, czy przekreślenie przekątnej od lewego dolnego do prawego górnego jest ukryte czy widoczne.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Przekreślenie od lewego górnego do prawego dolnego (wartość domyślna to false). Określa, czy przekreślenie przekątnej od lewego górnego do prawego dolnego jest ukryte czy widoczne.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Zwraca:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Przekreślenie od lewego górnego do prawego dolnego (wartość domyślna to false). Określa, czy przekreślenie przekątnej od lewego górnego do prawego dolnego jest ukryte czy widoczne.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Pobierz elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Właściwości znaków kontrolnych

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps