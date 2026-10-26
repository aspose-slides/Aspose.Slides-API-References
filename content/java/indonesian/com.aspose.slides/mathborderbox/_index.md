---
title: MathBorderBox
second_title: Referensi API Aspose.Slides untuk Java
description: Menggambar border persegi panjang atau border lain di sekitar IMathElement.
type: docs
url: /id/com.aspose.slides/mathborderbox/
---
**Warisan:** java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Menggambar border persegi panjang atau border lain di sekitar IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Membuat elemen MathBorderBox dengan border persegi panjang |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Membuat elemen MathBorderBox |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen dasar |
| [getHideTop()](#getHideTop--) | Sembunyikan Tepi Atas (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi atas kotak border. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Sembunyikan Tepi Atas (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi atas kotak border. |
| [getHideBottom()](#getHideBottom--) | Sembunyikan Tepi Bawah (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi bawah kotak border. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Sembunyikan Tepi Bawah (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi bawah kotak border. |
| [getHideLeft()](#getHideLeft--) | Sembunyikan Tepi Kiri (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi kiri kotak border. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Sembunyikan Tepi Kiri (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi kiri kotak border. |
| [getHideRight()](#getHideRight--) | Sembunyikan Tepi Kanan (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi kanan kotak border. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Sembunyikan Tepi Kanan (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi kanan kotak border. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Coret Mendatar (default false) - menentukan keadaan tersembunyi atau terlihat dari garis coret mendatar. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Coret Mendatar (default false) - menentukan keadaan tersembunyi atau terlihat dari garis coret mendatar. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Coret Vertikal (default false) - menentukan keadaan tersembunyi atau terlihat dari garis coret vertikal. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Coret Vertikal (default false) - menentukan keadaan tersembunyi atau terlihat dari garis coret vertikal. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Coret Diagonal dari Kiri-Bawah ke Kanan-Atas (default false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Coret Diagonal dari Kiri-Bawah ke Kanan-Atas (default false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Coret Diagonal dari Kiri-Atas ke Kanan-Bawah (default false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Coret Diagonal dari Kiri-Atas ke Kanan-Bawah (default false). |
| [getChildren()](#getChildren--) | Dapatkan elemen anak |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Membuat elemen MathBorderBox dengan border persegi panjang

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elemen dasar yang border box diterapkan. Bisa null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Membuat elemen MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elemen dasar yang border box diterapkan |
| hideTop | boolean | Sembunyikan Tepi Atas |
| hideBottom | boolean | Sembunyikan Tepi Bawah |
| hideLeft | boolean | Sembunyikan Tepi Kiri |
| hideRight | boolean | Sembunyikan Tepi Kanan |
| strikethroughHorizontal | boolean | Coret Mendatar |
| strikethroughVertical | boolean | Coret Vertikal |
| strikethroughBottomLeftToTopRight | boolean | Coret Diagonal dari Kiri-Bawah ke Kanan-Atas |
| strikethroughTopLeftToBottomRight | boolean | Coret Diagonal dari Kiri-Atas ke Kanan-Bawah |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argumen dasar

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Sembunyikan Tepi Atas (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi atas kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Mengembalikan:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Sembunyikan Tepi Atas (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi atas kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Sembunyikan Tepi Bawah (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi bawah kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Mengembalikan:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Sembunyikan Tepi Bawah (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi bawah kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Sembunyikan Tepi Kiri (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi kiri kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Mengembalikan:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Sembunyikan Tepi Kiri (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi kiri kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Sembunyikan Tepi Kanan (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi kanan kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Mengembalikan:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Sembunyikan Tepi Kanan (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi kanan kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Coret Mendatar (default false) - menentukan keadaan tersembunyi atau terlihat dari garis coret mendatar.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Mengembalikan:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Coret Mendatar (default false) - menentukan keadaan tersembunyi atau terlihat dari garis coret mendatar.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Coret Vertikal (default false) - menentukan keadaan tersembunyi atau terlihat dari garis coret vertikal.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Mengembalikan:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Coret Vertikal (default false) - menentukan keadaan tersembunyi atau terlihat dari garis coret vertikal.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Coret Diagonal dari Kiri-Bawah ke Kanan-Atas (default false). Menentukan keadaan tersembunyi atau terlihat dari garis coret diagonal dari sudut kiri-bawah ke sudut kanan-atas kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Mengembalikan:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Coret Diagonal dari Kiri-Bawah ke Kanan-Atas (default false). Menentukan keadaan tersembunyi atau terlihat dari garis coret diagonal dari sudut kiri-bawah ke sudut kanan-atas kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Coret Diagonal dari Kiri-Atas ke Kanan-Bawah (default false). Menentukan keadaan tersembunyi atau terlihat dari garis coret diagonal dari sudut kiri-atas ke sudut kanan-bawah kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Mengembalikan:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Coret Diagonal dari Kiri-Atas ke Kanan-Bawah (default false). Menentukan keadaan tersembunyi atau terlihat dari garis coret diagonal dari sudut kiri-atas ke sudut kanan-bawah kotak border.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Dapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Properti Karakter Kontrol

**Mengembalikan:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps