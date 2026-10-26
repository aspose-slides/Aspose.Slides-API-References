---
title: IMathBorderBox
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: IMathElement etrafında dikdörtgen ya da başka bir kenarlık çizer.
type: docs
url: /tr/com.aspose.slides/imathborderbox/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

IMathElement etrafında dikdörtgen veya başka bir kenarlık çizer.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getHideTop()](#getHideTop--) | Hide Top Edge (default is false) - kenar kutusunun üst kenarının gizli veya gösterili durumunu belirler. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (default is false) - kenar kutusunun üst kenarının gizli veya gösterili durumunu belirler. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (default is false) - kenar kutusunun alt kenarının gizli veya gösterili durumunu belirler. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (default is false) - kenar kutusunun alt kenarının gizli veya gösterili durumunu belirler. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (default is false) - kenar kutusunun sol kenarının gizli veya gösterili durumunu belirler. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (default is false) - kenar kutusunun sol kenarının gizli veya gösterili durumunu belirler. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (default is false) - kenar kutusunun sağ kenarının gizli veya gösterili durumunu belirler. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (default is false) - kenar kutusunun sağ kenarının gizli veya gösterili durumunu belirler. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (default is false) - yatay bir üstü çizili satırın gizli veya gösterili durumunu belirler. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (default is false) - yatay bir üstü çizili satırın gizli veya gösterili durumunu belirler. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (default is false) - dikey bir üstü çizili satırın gizli veya gösterili durumunu belirler. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (default is false) - dikey bir üstü çizili satırın gizli veya gösterili durumunu belirler. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (default is false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Temel argüman

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
>  ```


**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Hide Top Edge (default is false) - kenar kutusunun üst kenarının gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Döndürür:**  
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


Hide Top Edge (default is false) - kenar kutusunun üst kenarının gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```


Hide Bottom Edge (default is false) - kenar kutusunun alt kenarının gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Döndürür:**  
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


Hide Bottom Edge (default is false) - kenar kutusunun alt kenarının gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```


Hide Left Edge (default is false) - kenar kutusunun sol kenarının gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Döndürür:**  
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


Hide Left Edge (default is false) - kenar kutusunun sol kenarının gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```


Hide Right Edge (default is false) - kenar kutusunun sağ kenarının gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Döndürür:**  
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


Hide Right Edge (default is false) - kenar kutusunun sağ kenarının gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


Strikethrough Horizontal (default is false) - yatay bir üstü çizili satırın gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Döndürür:**  
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


Strikethrough Horizontal (default is false) - yatay bir üstü çizili satırın gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Strikethrough Vertical (default is false) - dikey bir üstü çizili satırın gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Döndürür:**  
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Strikethrough Vertical (default is false) - dikey bir üstü çizili satırın gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```


Strikethrough Bottom-Left to Top-Right (default is false). Alt-sol köşesinden üst-sağ köşeye doğru bir çapraz çizginin gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Döndürür:**  
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


Strikethrough Bottom-Left to Top-Right (default is false). Alt-sol köşesinden üst-sağ köşeye doğru bir çapraz çizginin gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


Strikethrough Top-Left to Bottom-Right (default is false). Üst-sol köşesinden alt-sağ köşeye doğru bir çapraz çizginin gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Döndürür:**  
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


Strikethrough Top-Left to Bottom-Right (default is false). Üst-sol köşesinden alt-sağ köşeye doğru bir çapraz çizginin gizli veya gösterili durumunu belirler.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |