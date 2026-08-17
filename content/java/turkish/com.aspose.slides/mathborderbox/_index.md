---
title: MathBorderBox
second_title: Aspose.Slides for Java API Referansı
description: IMathElement etrafına dikdörtgen veya başka bir kenarlık çizer.
type: docs
url: /tr/com.aspose.slides/mathborderbox/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

IMathElement etrafına dikdörtgen veya başka bir kenarlık çizer.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | MathBorderBox öğesini dikdörtgen kenarlık ile oluşturur |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | MathBorderBox öğesini oluşturur |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getHideTop()](#getHideTop--) | Üst Kenarı Gizle (varsayılan false) - kenarlık kutusunun üst kenarının gizli veya gösterili durumunu belirtir. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Üst Kenarı Gizle (varsayılan false) - kenarlık kutusunun üst kenarının gizli veya gösterili durumunu belirtir. |
| [getHideBottom()](#getHideBottom--) | Alt Kenarı Gizle (varsayılan false) - kenarlık kutusunun alt kenarının gizli veya gösterili durumunu belirtir. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Alt Kenarı Gizle (varsayılan false) - kenarlık kutusunun alt kenarının gizli veya gösterili durumunu belirtir. |
| [getHideLeft()](#getHideLeft--) | Sol Kenarı Gizle (varsayılan false) - kenarlık kutusunun sol kenarının gizli veya gösterili durumunu belirtir. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Sol Kenarı Gizle (varsayılan false) - kenarlık kutusunun sol kenarının gizli veya gösterili durumunu belirtir. |
| [getHideRight()](#getHideRight--) | Sağ Kenarı Gizle (varsayılan false) - kenarlık kutusunun sağ kenarının gizli veya gösterili durumunu belirtir. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Sağ Kenarı Gizle (varsayılan false) - kenarlık kutusunun sağ kenarının gizli veya gösterili durumunu belirtir. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Yatay Üstü Çizili (varsayılan false) - yatay bir üstü çizili çizginin gizli veya gösterili durumunu belirtir. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Yatay Üstü Çizili (varsayılan false) - yatay bir üstü çizili çizginin gizli veya gösterili durumunu belirtir. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Dikey Üstü Çizili (varsayılan false) - dikey bir üstü çizili çizginin gizli veya gösterili durumunu belirtir. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Dikey Üstü Çizili (varsayılan false) - dikey bir üstü çizili çizginin gizli veya gösterili durumunu belirtir. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Alt Sol'dan Üst Sağa Üstü Çizili (varsayılan false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Alt Sol'dan Üst Sağa Üstü Çizili (varsayılan false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Üst Sol'dan Alt Sağa Üstü Çizili (varsayılan false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Üst Sol'dan Alt Sağa Üstü Çizili (varsayılan false). |
| [getChildren()](#getChildren--) | Alt öğeleri al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

MathBorderBox öğesini dikdörtgen kenarlık ile oluşturur

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Kenarlık kutusunun uygulandığı temel öğe. Null olabilir. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

MathBorderBox öğesini oluşturur

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Kenarlık kutusunun uygulandığı temel öğe |
| hideTop | boolean | Üst Kenarı Gizle |
| hideBottom | boolean | Alt Kenarı Gizle |
| hideLeft | boolean | Sol Kenarı Gizle |
| hideRight | boolean | Sağ Kenarı Gizle |
| strikethroughHorizontal | boolean | Yatay Üstü Çizili |
| strikethroughVertical | boolean | Dikey Üstü Çizili |
| strikethroughBottomLeftToTopRight | boolean | Alt Sol'dan Üst Sağa Üstü Çizili |
| strikethroughTopLeftToBottomRight | boolean | Üst Sol'dan Alt Sağa Üstü Çizili |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Temel argüman

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Üst Kenarı Gizle (varsayılan false) - kenarlık kutusunun üst kenarının gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Döndürür:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Üst Kenarı Gizle (varsayılan false) - kenarlık kutusunun üst kenarının gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Alt Kenarı Gizle (varsayılan false) - kenarlık kutusunun alt kenarının gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Döndürür:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Alt Kenarı Gizle (varsayılan false) - kenarlık kutusunun alt kenarının gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Sol Kenarı Gizle (varsayılan false) - kenarlık kutusunun sol kenarının gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Döndürür:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Sol Kenarı Gizle (varsayılan false) - kenarlık kutusunun sol kenarının gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Sağ Kenarı Gizle (varsayılan false) - kenarlık kutusunun sağ kenarının gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Döndürür:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Sağ Kenarı Gizle (varsayılan false) - kenarlık kutusunun sağ kenarının gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Yatay Üstü Çizili (varsayılan false) - yatay bir üstü çizili çizginin gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Döndürür:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Yatay Üstü Çizili (varsayılan false) - yatay bir üstü çizili çizginin gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Dikey Üstü Çizili (varsayılan false) - dikey bir üstü çizili çizginin gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Döndürür:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Dikey Üstü Çizili (varsayılan false) - dikey bir üstü çizili çizginin gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Alt Sol'dan Üst Sağa Üstü Çizili (varsayılan false). Alt sol köşeden üst sağ köşeye bir çapraz üstü çizili çizginin gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Döndürür:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Alt Sol'dan Üst Sağa Üstü Çizili (varsayılan false). Alt sol köşeden üst sağ köşeye bir çapraz üstü çizili çizginin gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Üst Sol'dan Alt Sağa Üstü Çizili (varsayılan false). Üst sol köşeden alt sağ köşeye bir çapraz üstü çizili çizginin gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Döndürür:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Üst Sol'dan Alt Sağa Üstü Çizili (varsayılan false). Üst sol köşeden alt sağ köşeye bir çapraz üstü çizili çizginin gizli veya gösterili durumunu belirtir.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Alt öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrol Karakteri Özellikleri

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps