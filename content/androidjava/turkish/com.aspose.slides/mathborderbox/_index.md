---
title: MathBorderBox
second_title: Aspose.Slides for Android Java API Referansı aracılığıyla
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
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Dikdörtgen kenarlıklı MathBorderBox öğesi oluşturur |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | MathBorderBox öğesi oluşturur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getHideTop()](#getHideTop--) | Üst Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun üst kenarının gizli veya gösterili durumunu belirler. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Üst Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun üst kenarının gizli veya gösterili durumunu belirler. |
| [getHideBottom()](#getHideBottom--) | Alt Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun alt kenarının gizli veya gösterili durumunu belirler. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Alt Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun alt kenarının gizli veya gösterili durumunu belirler. |
| [getHideLeft()](#getHideLeft--) | Sol Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun sol kenarının gizli veya gösterili durumunu belirler. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Sol Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun sol kenarının gizli veya gösterili durumunu belirler. |
| [getHideRight()](#getHideRight--) | Sağ Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun sağ kenarının gizli veya gösterili durumunu belirler. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Sağ Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun sağ kenarının gizli veya gösterili durumunu belirler. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Yatay Üzeri Çizili (varsayılan false'tur) - yatay bir üzeri çizgi satırının gizli veya gösterili durumunu belirler. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Yatay Üzeri Çizili (varsayılan false'tur) - yatay bir üzeri çizgi satırının gizli veya gösterili durumunu belirler. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Dikey Üzeri Çizili (varsayılan false'tur) - dikey bir üzeri çizgi satırının gizli veya gösterili durumunu belirler. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Dikey Üzeri Çizili (varsayılan false'tur) - dikey bir üzeri çizgi satırının gizli veya gösterili durumunu belirler. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Alt Sol'dan Üst Sağ'a Üzeri Çizili (varsayılan false'tur). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Alt Sol'dan Üst Sağ'a Üzeri Çizili (varsayılan false'tur). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Üst Sol'dan Alt Sağ'a Üzeri Çizili (varsayılan false'tur). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Üst Sol'dan Alt Sağ'a Üzeri Çizili (varsayılan false'tur). |
| [getChildren()](#getChildren--) | Alt öğeleri al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Dikdörtgen kenarlıklı MathBorderBox öğesi oluşturur

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

MathBorderBox öğesi oluşturur

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
| strikethroughHorizontal | boolean | Yatay Üzeri Çizili |
| strikethroughVertical | boolean | Dikey Üzeri Çizili |
| strikethroughBottomLeftToTopRight | boolean | Alt Sol'dan Üst Sağ'a Üzeri Çizili |
| strikethroughTopLeftToBottomRight | boolean | Üst Sol'dan Alt Sağ'a Üzeri Çizili |

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

Üst Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun üst kenarının gizli veya gösterili durumunu belirler.

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

Üst Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun üst kenarının gizli veya gösterili durumunu belirler.

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

Alt Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun alt kenarının gizli veya gösterili durumunu belirler.

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

Alt Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun alt kenarının gizli veya gösterili durumunu belirler.

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

Sol Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun sol kenarının gizli veya gösterili durumunu belirler.

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

Sol Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun sol kenarının gizli veya gösterili durumunu belirler.

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

Sağ Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun sağ kenarının gizli veya gösterili durumunu belirler.

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

Sağ Kenarı Gizle (varsayılan false'tur) - kenarlık kutusunun sağ kenarının gizli veya gösterili durumunu belirler.

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

Yatay Üzeri Çizili (varsayılan false'tur) - yatay bir üzeri çizgi satırının gizli veya gösterili durumunu belirler.

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

Yatay Üzeri Çizili (varsayılan false'tur) - yatay bir üzeri çizgi satırının gizli veya gösterili durumunu belirler.

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

Dikey Üzeri Çizili (varsayılan false'tur) - dikey bir üzeri çizgi satırının gizli veya gösterili durumunu belirler.

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

Dikey Üzeri Çizili (varsayılan false'tur) - dikey bir üzeri çizgi satırının gizli veya gösterili durumunu belirler.

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

Alt Sol'dan Üst Sağ'a Üzeri Çizili (varsayılan false'tur). Kenarlık kutusunun alt sol köşesinden üst sağ köşesine doğru çapraz bir üzeri çizgi satırının gizli veya gösterili durumunu belirler.

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

Alt Sol'dan Üst Sağ'a Üzeri Çizili (varsayılan false'tur). Kenarlık kutusunun alt sol köşesinden üst sağ köşesine doğru çapraz bir üzeri çizgi satırının gizli veya gösterili durumunu belirler.

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

Üst Sol'dan Alt Sağ'a Üzeri Çizili (varsayılan false'tur). Kenarlık kutusunun üst sol köşesinden alt sağ köşesine doğru çapraz bir üzeri çizgi satırının gizli veya gösterili durumunu belirler.

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

Üst Sol'dan Alt Sağ'a Üzeri Çizili (varsayılan false'tur). Kenarlık kutusunun üst sol köşesinden alt sağ köşesine doğru çapraz bir üzeri çizgi satırının gizli veya gösterili durumunu belirler.

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