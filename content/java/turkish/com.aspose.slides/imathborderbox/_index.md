---
title: IMathBorderBox
second_title: Aspose.Slides for Java API Referansı
description: IMathElement etrafına dikdörtgen veya başka bir kenarlık çizer.
type: docs
url: /tr/com.aspose.slides/imathborderbox/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

IMathElement etrafına dikdörtgen veya başka bir kenarlık çizer.

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
| [getHideTop()](#getHideTop--) | Üst Kenarı Gizle (varsayılan false) - kenarlık kutusunun üst kenarının gizli ya da görünür durumunu belirtir. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Üst Kenarı Gizle (varsayılan false) - kenarlık kutusunun üst kenarının gizli ya da görünür durumunu belirtir. |
| [getHideBottom()](#getHideBottom--) | Alt Kenarı Gizle (varsayılan false) - kenarlık kutusunun alt kenarının gizli ya da görünür durumunu belirtir. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Alt Kenarı Gizle (varsayılan false) - kenarlık kutusunun alt kenarının gizli ya da görünür durumunu belirtir. |
| [getHideLeft()](#getHideLeft--) | Sol Kenarı Gizle (varsayılan false) - kenarlık kutusunun sol kenarının gizli ya da görünür durumunu belirtir. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Sol Kenarı Gizle (varsayılan false) - kenarlık kutusunun sol kenarının gizli ya da görünür durumunu belirtir. |
| [getHideRight()](#getHideRight--) | Sağ Kenarı Gizle (varsayılan false) - kenarlık kutusunun sağ kenarının gizli ya da görünür durumunu belirtir. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Sağ Kenarı Gizle (varsayılan false) - kenarlık kutusunun sağ kenarının gizli ya da görünür durumunu belirtir. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Yatay Üstü Çizili (varsayılan false) - yatay bir üstü çizili çizginin gizli ya da görünür durumunu belirtir. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Yatay Üstü Çizili (varsayılan false) - yatay bir üstü çizili çizginin gizli ya da görünür durumunu belirtir. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Dikey Üstü Çizili (varsayılan false) - dikey bir üstü çizili çizginin gizli ya da görünür durumunu belirtir. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Dikey Üstü Çizili (varsayılan false) - dikey bir üstü çizili çizginin gizli ya da görünür durumunu belirtir. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Alt Sol'dan Üst Sağa Üstü Çizili (varsayılan false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Alt Sol'dan Üst Sağa Üstü Çizili (varsayılan false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Üst Sol'dan Alt Sağa Üstü Çizili (varsayılan false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Üst Sol'dan Alt Sağa Üstü Çizili (varsayılan false). |

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

Üst Kenarı Gizle (varsayılan false) - kenarlık kutusunun üst kenarının gizli ya da görünür durumunu belirtir.

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

Üst Kenarı Gizle (varsayılan false) - kenarlık kutusunun üst kenarının gizli ya da görünür durumunu belirtir.

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

Alt Kenarı Gizle (varsayılan false) - kenarlık kutusunun alt kenarının gizli ya da görünür durumunu belirtir.

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

Alt Kenarı Gizle (varsayılan false) - kenarlık kutusunun alt kenarının gizli ya da görünür durumunu belirtir.

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

Sol Kenarı Gizle (varsayılan false) - kenarlık kutusunun sol kenarının gizli ya da görünür durumunu belirtir.

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

Sol Kenarı Gizle (varsayılan false) - kenarlık kutusunun sol kenarının gizli ya da görünür durumunu belirtir.

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

Sağ Kenarı Gizle (varsayılan false) - kenarlık kutusunun sağ kenarının gizli ya da görünür durumunu belirtir.

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

Sağ Kenarı Gizle (varsayılan false) - kenarlık kutusunun sağ kenarının gizli ya da görünür durumunu belirtir.

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

Yatay Üstü Çizili (varsayılan false) - yatay bir üstü çizili çizginin gizli ya da görünür durumunu belirtir.

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

Yatay Üstü Çizili (varsayılan false) - yatay bir üstü çizili çizginin gizli ya da görünür durumunu belirtir.

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

Dikey Üstü Çizili (varsayılan false) - dikey bir üstü çizili çizginin gizli ya da görünür durumunu belirtir.

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

Dikey Üstü Çizili (varsayılan false) - dikey bir üstü çizili çizginin gizli ya da görünür durumunu belirtir.

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

Alt Sol'dan Üst Sağa Üstü Çizili (varsayılan false). Kenarlık kutusunun alt-sol köşesinden üst-sağ köşesine uzanan bir çapraz üstü çizili çizginin gizli ya da görünür durumunu belirtir.

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

Alt Sol'dan Üst Sağa Üstü Çizili (varsayılan false). Kenarlık kutusunun alt-sol köşesinden üst-sağ köşesine uzanan bir çapraz üstü çizili çizginin gizli ya da görünür durumunu belirtir.

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

Üst Sol'dan Alt Sağa Üstü Çizili (varsayılan false). Kenarlık kutusunun üst-sol köşesinden alt-sağ köşesine uzanan bir çapraz üstü çizili çizginin gizli ya da görünür durumunu belirtir.

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

Üst Sol'dan Alt Sağa Üstü Çizili (varsayılan false). Kenarlık kutusunun üst-sol köşesinden alt-sağ köşesine uzanan bir çapraz üstü çizili çizginin gizli ya da görünür durumunu belirtir.

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