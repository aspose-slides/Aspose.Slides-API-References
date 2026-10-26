---
title: IMathBorderBox
second_title: Referensi API Aspose.Slides untuk Java
description: Menggambar persegi panjang atau batas lain di sekitar IMathElement.
type: docs
url: /id/com.aspose.slides/imathborderbox/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Menggambar sebuah persegi panjang atau batas lain di sekitar IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen dasar |
| [getHideTop()](#getHideTop--) | Sembunyikan Tepian Atas (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi atas kotak batas. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Sembunyikan Tepian Atas (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi atas kotak batas. |
| [getHideBottom()](#getHideBottom--) | Sembunyikan Tepian Bawah (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi bawah kotak batas. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Sembunyikan Tepian Bawah (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi bawah kotak batas. |
| [getHideLeft()](#getHideLeft--) | Sembunyikan Tepian Kiri (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi kiri kotak batas. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Sembunyikan Tepian Kiri (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi kiri kotak batas. |
| [getHideRight()](#getHideRight--) | Sembunyikan Tepian Kanan (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi kanan kotak batas. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Sembunyikan Tepian Kanan (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi kanan kotak batas. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Garis coret Horizontal (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari garis coret horizontal. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Garis coret Horizontal (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari garis coret horizontal. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Garis coret Vertikal (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari garis coret vertikal. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Garis coret Vertikal (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari garis coret vertikal. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Garis coret dari Kiri-Bawah ke Kanan-Atas (default adalah false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Garis coret dari Kiri-Bawah ke Kanan-Atas (default adalah false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Garis coret dari Kiri-Atas ke Kanan-Bawah (default adalah false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Garis coret dari Kiri-Atas ke Kanan-Bawah (default adalah false). |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumen dasar

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

Sembunyikan Tepian Atas (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi atas kotak batas.

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

Sembunyikan Tepian Atas (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi atas kotak batas.

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

Sembunyikan Tepian Bawah (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi bawah kotak batas.

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

Sembunyikan Tepian Bawah (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi bawah kotak batas.

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

Sembunyikan Tepian Kiri (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi kiri kotak batas.

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

Sembunyikan Tepian Kiri (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi kiri kotak batas.

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

Sembunyikan Tepian Kanan (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi kanan kotak batas.

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

Sembunyikan Tepian Kanan (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari tepi kanan kotak batas.

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

Garis coret Horizontal (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari garis coret horizontal.

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

Garis coret Horizontal (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari garis coret horizontal.

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

Garis coret Vertikal (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari garis coret vertikal.

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

Garis coret Vertikal (default adalah false) - menentukan keadaan tersembunyi atau ditampilkan dari garis coret vertikal.

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

Garis coret dari Kiri-Bawah ke Kanan-Atas (default adalah false). Menentukan keadaan tersembunyi atau ditampilkan dari garis coret diagonal dari sudut kiri-bawah ke sudut kanan-atas kotak batas.

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

Garis coret dari Kiri-Bawah ke Kanan-Atas (default adalah false). Menentukan keadaan tersembunyi atau ditampilkan dari garis coret diagonal dari sudut kiri-bawah ke sudut kanan-atas kotak batas.

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

Garis coret dari Kiri-Atas ke Kanan-Bawah (default adalah false). Menentukan keadaan tersembunyi atau ditampilkan dari garis coret diagonal dari sudut kiri-atas ke sudut kanan-bawah kotak batas.

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

Garis coret dari Kiri-Atas ke Kanan-Bawah (default adalah false). Menentukan keadaan tersembunyi atau ditampilkan dari garis coret diagonal dari sudut kiri-atas ke sudut kanan-bawah kotak batas.

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