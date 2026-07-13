---
title: IColorFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili warna yang digunakan dalam presentasi.
type: docs
url: /id/com.aspose.slides/icolorformat/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Mewakili warna yang digunakan dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColorType()](#getColorType--) | Mengembalikan atau mengatur metode definisi warna. |
| [setColorType(int value)](#setColorType-int-) | Mengembalikan atau mengatur metode definisi warna. |
| [getColor()](#getColor--) | Mengembalikan warna hasil (dengan semua transformasi warna diterapkan). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Mengembalikan warna hasil (dengan semua transformasi warna diterapkan). |
| [getPresetColor()](#getPresetColor--) | Mengembalikan atau mengatur preset warna. |
| [setPresetColor(int value)](#setPresetColor-int-) | Mengembalikan atau mengatur preset warna. |
| [getSystemColor()](#getSystemColor--) | Mengembalikan atau mengatur warna yang diidentifikasi oleh tabel warna sistem. |
| [setSystemColor(int value)](#setSystemColor-int-) | Mengembalikan atau mengatur warna yang diidentifikasi oleh tabel warna sistem. |
| [getSchemeColor()](#getSchemeColor--) | Mengembalikan atau mengatur warna yang diidentifikasi oleh skema warna. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Mengembalikan atau mengatur warna yang diidentifikasi oleh skema warna. |
| [getR()](#getR--) | Mengembalikan atau mengatur komponen merah dari sebuah warna. |
| [setR(byte value)](#setR-byte-) | Mengembalikan atau mengatur komponen merah dari sebuah warna. |
| [getG()](#getG--) | Mengembalikan atau mengatur komponen hijau dari sebuah warna. |
| [setG(byte value)](#setG-byte-) | Mengembalikan atau mengatur komponen hijau dari sebuah warna. |
| [getB()](#getB--) | Mengembalikan atau mengatur komponen biru dari sebuah warna. |
| [setB(byte value)](#setB-byte-) | Mengembalikan atau mengatur komponen biru dari sebuah warna. |
| [getFloatR()](#getFloatR--) | Mengembalikan atau mengatur komponen merah dari sebuah warna. |
| [setFloatR(float value)](#setFloatR-float-) | Mengembalikan atau mengatur komponen merah dari sebuah warna. |
| [getFloatG()](#getFloatG--) | Mengembalikan atau mengatur komponen hijau dari sebuah warna. |
| [setFloatG(float value)](#setFloatG-float-) | Mengembalikan atau mengatur komponen hijau dari sebuah warna. |
| [getFloatB()](#getFloatB--) | Mengembalikan atau mengatur komponen biru dari sebuah warna. |
| [setFloatB(float value)](#setFloatB-float-) | Mengembalikan atau mengatur komponen biru dari sebuah warna. |
| [getHue()](#getHue--) | Mengembalikan atau mengatur komponen hue dari sebuah warna dalam representasi HSL. |
| [setHue(float value)](#setHue-float-) | Mengembalikan atau mengatur komponen hue dari sebuah warna dalam representasi HSL. |
| [getSaturation()](#getSaturation--) | Mengembalikan atau mengatur komponen saturasi dari sebuah warna dalam representasi HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Mengembalikan atau mengatur komponen saturasi dari sebuah warna dalam representasi HSL. |
| [getLuminance()](#getLuminance--) | Mengembalikan atau mengatur komponen luminansi dari sebuah warna dalam representasi HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Mengembalikan atau mengatur komponen luminansi dari sebuah warna dalam representasi HSL. |
| [getColorTransform()](#getColorTransform--) | Mengembalikan koleksi transformasi warna yang diterapkan pada sebuah warna. |
| [toString(int format)](#toString-int-) | Mengembalikan String yang merepresentasikan format warna saat ini. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Menyalin format warna dari "color". |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Mengembalikan atau mengatur metode definisi warna. Baca/tulis [ColorType](../../com.aspose.slides/colortype).

**Mengembalikan:**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Mengembalikan atau mengatur metode definisi warna. Baca/tulis [ColorType](../../com.aspose.slides/colortype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Mengembalikan warna hasil (dengan semua transformasi warna diterapkan). Mengatur warna RGB dan menghapus semua transformasi warna. Baca/tulis java.lang.Integer.

**Mengembalikan:**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Mengembalikan warna hasil (dengan semua transformasi warna diterapkan). Mengatur warna RGB dan menghapus semua transformasi warna. Baca/tulis java.lang.Integer.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Mengembalikan atau mengatur preset warna. Baca/tulis [PresetColor](../../com.aspose.slides/presetcolor).

**Mengembalikan:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Mengembalikan atau mengatur preset warna. Baca/tulis [PresetColor](../../com.aspose.slides/presetcolor).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Mengembalikan atau mengatur warna yang diidentifikasi oleh tabel warna sistem. Baca/tulis [SystemColor](../../com.aspose.slides/systemcolor).

**Mengembalikan:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Mengembalikan atau mengatur warna yang diidentifikasi oleh tabel warna sistem. Baca/tulis [SystemColor](../../com.aspose.slides/systemcolor).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Mengembalikan atau mengatur warna yang diidentifikasi oleh skema warna. Baca/tulis [SchemeColor](../../com.aspose.slides/schemecolor).

**Mengembalikan:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Mengembalikan atau mengatur warna yang diidentifikasi oleh skema warna. Baca/tulis [SchemeColor](../../com.aspose.slides/schemecolor).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

Mengembalikan atau mengatur komponen merah dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis byte.

**Mengembalikan:**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Mengembalikan atau mengatur komponen merah dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

Mengembalikan atau mengatur komponen hijau dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis byte.

**Mengembalikan:**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Mengembalikan atau mengatur komponen hijau dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

Mengembalikan atau mengatur komponen biru dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis byte.

**Mengembalikan:**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Mengembalikan atau mengatur komponen biru dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Mengembalikan atau mengatur komponen merah dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis float.

**Mengembalikan:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Mengembalikan atau mengatur komponen merah dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Mengembalikan atau mengatur komponen hijau dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis float.

**Mengembalikan:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Mengembalikan atau mengatur komponen hijau dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Mengembalikan atau mengatur komponen biru dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis float.

**Mengembalikan:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Mengembalikan atau mengatur komponen biru dari sebuah warna. Semua transformasi warna diabaikan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

Mengembalikan atau mengatur komponen hue dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca/tulis float.

**Mengembalikan:**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Mengembalikan atau mengatur komponen hue dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Mengembalikan atau mengatur komponen saturasi dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca/tulis float.

**Mengembalikan:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Mengembalikan atau mengatur komponen saturasi dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Mengembalikan atau mengatur komponen luminansi dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca/tulis float.

**Mengembalikan:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Mengembalikan atau mengatur komponen luminansi dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Mengembalikan koleksi transformasi warna yang diterapkan pada sebuah warna. Hanya-baca [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Mengembalikan:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Mengembalikan String yang merepresentasikan format warna saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | int | Jenis format string warna. |

**Mengembalikan:**
java.lang.String - String yang merepresentasikan format warna saat ini.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Menyalin format warna dari "color".

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Warna [IColorFormat](../../com.aspose.slides/icolorformat) |