---
title: IMathBorderBox
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menggambar border persegi panjang atau jenis lain di sekitar IMathElement.
type: docs
url: /id/com.aspose.slides/imathborderbox/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Menggambar sebuah border persegi panjang atau jenis lain di sekitar IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argument dasar |
| [getHideTop()](#getHideTop--) | Sembunyikan Tepi Atas (default false) - menentukan apakah tepi atas kotak border disembunyikan atau ditampilkan. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Sembunyikan Tepi Atas (default false) - menentukan apakah tepi atas kotak border disembunyikan atau ditampilkan. |
| [getHideBottom()](#getHideBottom--) | Sembunyikan Tepi Bawah (default false) - menentukan apakah tepi bawah kotak border disembunyikan atau ditampilkan. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Sembunyikan Tepi Bawah (default false) - menentukan apakah tepi bawah kotak border disembunyikan atau ditampilkan. |
| [getHideLeft()](#getHideLeft--) | Sembunyikan Tepi Kiri (default false) - menentukan apakah tepi kiri kotak border disembunyikan atau ditampilkan. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Sembunyikan Tepi Kiri (default false) - menentukan apakah tepi kiri kotak border disembunyikan atau ditampilkan. |
| [getHideRight()](#getHideRight--) | Sembunyikan Tepi Kanan (default false) - menentukan apakah tepi kanan kotak border disembunyikan atau ditampilkan. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Sembunyikan Tepi Kanan (default false) - menentukan apakah tepi kanan kotak border disembunyikan atau ditampilkan. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Garis Coret Horizontal (default false) - menentukan apakah garis coret horizontal disembunyikan atau ditampilkan. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Garis Coret Horizontal (default false) - menentukan apakah garis coret horizontal disembunyikan atau ditampilkan. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Garis Coret Vertikal (default false) - menentukan apakah garis coret vertikal disembunyikan atau ditampilkan. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Garis Coret Vertikal (default false) - menentukan apakah garis coret vertikal disembunyikan atau ditampilkan. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Garis Coret Diagonal dari Kiri-Bawah ke Kanan-Atas (default false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Garis Coret Diagonal dari Kiri-Bawah ke Kanan-Atas (default false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Garis Coret Diagonal dari Kiri-Atas ke Kanan-Bawah (default false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Garis Coret Diagonal dari Kiri-Atas ke Kanan-Bawah (default false). |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument dasar

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```


**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

Sembunyikan Tepi Atas (default false) - menentukan apakah tepi atas kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Mengembalikan:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

Sembunyikan Tepi Atas (default false) - menentukan apakah tepi atas kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

Sembunyikan Tepi Bawah (default false) - menentukan apakah tepi bawah kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```


**Mengembalikan:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

Sembunyikan Tepi Bawah (default false) - menentukan apakah tepi bawah kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

Sembunyikan Tepi Kiri (default false) - menentukan apakah tepi kiri kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Mengembalikan:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

Sembunyikan Tepi Kiri (default false) - menentukan apakah tepi kiri kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

Sembunyikan Tepi Kanan (default false) - menentukan apakah tepi kanan kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Mengembalikan:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

Sembunyikan Tepi Kanan (default false) - menentukan apakah tepi kanan kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

Garis Coret Horizontal (default false) - menentukan apakah garis coret horizontal disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Mengembalikan:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

Garis Coret Horizontal (default false) - menentukan apakah garis coret horizontal disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

Garis Coret Vertikal (default false) - menentukan apakah garis coret vertikal disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Mengembalikan:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

Garis Coret Vertikal (default false) - menentukan apakah garis coret vertikal disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Garis Coret Diagonal dari Kiri-Bawah ke Kanan-Atas (default false). Menentukan apakah garis coret diagonal dari sudut kiri-bawah ke sudut kanan-atas kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Mengembalikan:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

Garis Coret Diagonal dari Kiri-Bawah ke Kanan-Atas (default false). Menentukan apakah garis coret diagonal dari sudut kiri-bawah ke sudut kanan-atas kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Garis Coret Diagonal dari Kiri-Atas ke Kanan-Bawah (default false). Menentukan apakah garis coret diagonal dari sudut kiri-atas ke sudut kanan-bawah kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Mengembalikan:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

Garis Coret Diagonal dari Kiri-Atas ke Kanan-Bawah (default false). Menentukan apakah garis coret diagonal dari sudut kiri-atas ke sudut kanan-bawah kotak border disembunyikan atau ditampilkan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |