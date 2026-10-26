---
title: MathPhantom
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Merepresentasikan objek matematika phantom ltmphantgt yang memengaruhi tata letak elemen anaknya tanpa harus menampilkannya.
type: docs
url: /id/com.aspose.slides/mathphantom/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Menrepresentasikan objek matematika phantom (<m:phant>) yang mempengaruhi tata letak elemen anaknya tanpa harus menampilkannya. Sebuah phantom dapat menyembunyikan ekspresi dasarnya sambil mempertahankan lebar, tinggi, atau kedalamannya untuk menyelaraskan formula atau memesan ruang. Visibilitas dan perilaku geometris dikendalikan oleh properti seperti Show, ZeroWid, ZeroAsc, ZeroDesc, dan Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Sembunyikan konten
>  phantom.setZeroWidth(false);     // Pertahankan lebar
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Menginisialisasi sebuah instance baru dari kelas [MathPhantom](../../com.aspose.slides/mathphantom) menggunakan elemen matematika dasar yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen dasar |
| [getShow()](#getShow--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah elemen dasar ditampilkan. |
| [setShow(boolean value)](#setShow-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah elemen dasar ditampilkan. |
| [getZeroWidth()](#getZeroWidth--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar elemen dasar harus diperlakukan sebagai nol. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar elemen dasar harus diperlakukan sebagai nol. |
| [getZeroAsc()](#getZeroAsc--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah ascent (tinggi di atas baseline) elemen dasar harus diperlakukan sebagai nol. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah ascent (tinggi di atas baseline) elemen dasar harus diperlakukan sebagai nol. |
| [getZeroDesc()](#getZeroDesc--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah descent (kedalaman di bawah baseline) elemen dasar harus diperlakukan sebagai nol. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah descent (kedalaman di bawah baseline) elemen dasar harus diperlakukan sebagai nol. |
| [getTransp()](#getTransp--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah phantom transparan untuk aturan spasi berbasis kelas. |
| [setTransp(boolean value)](#setTransp-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah phantom transparan untuk aturan spasi berbasis kelas. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |
| [getChildren()](#getChildren--) | Mendapatkan elemen anak |

### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Menginisialisasi sebuah instance baru dari kelas [MathPhantom](../../com.aspose.slides/mathphantom) menggunakan elemen matematika dasar yang ditentukan.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elemen dasar [IMathElement](../../com.aspose.slides/imathelement) yang visibilitas dan tata letaknya akan dikendalikan oleh phantom. Elemen ini mendefinisikan konten yang dapat disembunyikan atau ditampilkan, sambil tetap mempengaruhi penyelarasan geometris matematika di sekitarnya. |

--------------------

Elemen phantom digunakan untuk memesan atau menekan ruang visual dari ekspresi dasarnya tanpa harus menampilkannya. Ini sesuai dengan elemen OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argumen dasar

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Return:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah elemen dasar ditampilkan.

--------------------

Jika false, elemen dasar disembunyikan tetapi tetap dapat menempati ruang tergantung pada pengaturan phantom lainnya. Sesuai dengan atribut OMML m:show.

**Return:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah elemen dasar ditampilkan.

--------------------

Jika false, elemen dasar disembunyikan tetapi tetap dapat menempati ruang tergantung pada pengaturan phantom lainnya. Sesuai dengan atribut OMML m:show.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar elemen dasar harus diperlakukan sebagai nol.

--------------------

Jika true, phantom tidak memesan ruang horizontal untuk dasarnya. Sesuai dengan atribut OMML m:zeroWid.

**Return:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar elemen dasar harus diperlakukan sebagai nol.

--------------------

Jika true, phantom tidak memesan ruang horizontal untuk dasarnya. Sesuai dengan atribut OMML m:zeroWid.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah ascent (tinggi di atas baseline) elemen dasar harus diperlakukan sebagai nol.

--------------------

Jika true, phantom tidak menaikkan baseline dari baris matematika di sekitarnya. Sesuai dengan atribut OMML m:zeroAsc.

**Return:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah ascent (tinggi di atas baseline) elemen dasar harus diperlakukan sebagai nol.

--------------------

Jika true, phantom tidak menaikkan baseline dari baris matematika di sekitarnya. Sesuai dengan atribut OMML m:zeroAsc.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah descent (kedalaman di bawah baseline) elemen dasar harus diperlakukan sebagai nol.

--------------------

Jika true, phantom tidak menurunkan baseline dari baris matematika di sekitarnya. Sesuai dengan atribut OMML m:zeroDesc.

**Return:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah descent (kedalaman di bawah baseline) elemen dasar harus diperlakukan sebagai nol.

--------------------

Jika true, phantom tidak menurunkan baseline dari baris matematika di sekitarnya. Sesuai dengan atribut OMML m:zeroDesc.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah phantom transparan untuk aturan spasi berbasis kelas.

--------------------

Jika true, operator dan simbol di dalam phantom tetap mempengaruhi spasi matematika di sekitarnya (seolah terlihat). Jika false, aturan spasi berbasis kelas diabaikan. Sesuai dengan atribut OMML m:transp.

**Return:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah phantom transparan untuk aturan spasi berbasis kelas.

--------------------

Jika true, operator dan simbol di dalam phantom tetap mempengaruhi spasi matematika di sekitarnya (seolah terlihat). Jika false, aturan spasi berbasis kelas diabaikan. Sesuai dengan atribut OMML m:transp.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Properti Karakter Kontrol

**Return:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Mendapatkan elemen anak

**Return:**
com.aspose.slides.IMathElement[]