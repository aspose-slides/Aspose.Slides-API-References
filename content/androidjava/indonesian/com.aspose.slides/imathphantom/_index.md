---
title: IMathPhantom
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili objek matematika phantom ltmphantgt yang memengaruhi tata letak elemen anaknya tanpa harus menampilkannya.
type: docs
url: /id/com.aspose.slides/imathphantom/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Mewakili objek matematika phantom (<m:phant>) yang memengaruhi tata letak elemen anaknya tanpa harus menampilkannya. Sebuah phantom dapat menyembunyikan ekspresi dasarnya sambil mempertahankan lebar, tinggi, atau kedalaman untuk menyelaraskan formula atau memesan ruang. Visibilitas dan perilaku geometri dikendalikan oleh properti seperti Show, ZeroWid, ZeroAsc, ZeroDesc, dan Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Sembunyikan konten
>  phantom.setZeroWidth(false);     // Pertahankan lebar
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen dasar |
| [getShow()](#getShow--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah elemen dasar ditampilkan. |
| [setShow(boolean value)](#setShow-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah elemen dasar ditampilkan. |
| [getZeroWidth()](#getZeroWidth--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar elemen dasar diperlakukan sebagai nol. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar elemen dasar diperlakukan sebagai nol. |
| [getZeroAsc()](#getZeroAsc--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah naik (tinggi di atas garis dasar) elemen dasar diperlakukan sebagai nol. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah naik (tinggi di atas garis dasar) elemen dasar diperlakukan sebagai nol. |
| [getZeroDesc()](#getZeroDesc--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah turun (kedalaman di bawah garis dasar) elemen dasar diperlakukan sebagai nol. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah turun (kedalaman di bawah garis dasar) elemen dasar diperlakukan sebagai nol. |
| [getTransp()](#getTransp--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah phantom transparan untuk aturan spasi berbasis kelas. |
| [setTransp(boolean value)](#setTransp-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah phantom transparan untuk aturan spasi berbasis kelas. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumen dasar

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah elemen dasar ditampilkan.

--------------------

Ketika false, elemen dasar disembunyikan tetapi masih dapat menempati ruang tergantung pada pengaturan phantom lainnya. Berhubungan dengan atribut OMML m:show.

**Mengembalikan:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah elemen dasar ditampilkan.

--------------------

Ketika false, elemen dasar disembunyikan tetapi masih dapat menempati ruang tergantung pada pengaturan phantom lainnya. Berhubungan dengan atribut OMML m:show.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar elemen dasar diperlakukan sebagai nol.

--------------------

Ketika true, phantom tidak memesan ruang horizontal untuk dasarnya. Berhubungan dengan atribut OMML m:zeroWid.

**Mengembalikan:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar elemen dasar diperlakukan sebagai nol.

--------------------

Ketika true, phantom tidak memesan ruang horizontal untuk dasarnya. Berhubungan dengan atribut OMML m:zeroWid.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah naik (tinggi di atas garis dasar) elemen dasar diperlakukan sebagai nol.

--------------------

Ketika true, phantom tidak menaikkan garis dasar baris matematika di sekitarnya. Berhubungan dengan atribut OMML m:zeroAsc.

**Mengembalikan:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah naik (tinggi di atas garis dasar) elemen dasar diperlakukan sebagai nol.

--------------------

Ketika true, phantom tidak menaikkan garis dasar baris matematika di sekitarnya. Berhubungan dengan atribut OMML m:zeroAsc.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah turun (kedalaman di bawah garis dasar) elemen dasar diperlakukan sebagai nol.

--------------------

Ketika true, phantom tidak menurunkan garis dasar baris matematika di sekitarnya. Berhubungan dengan atribut OMML m:zeroDesc.

**Mengembalikan:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah turun (kedalaman di bawah garis dasar) elemen dasar diperlakukan sebagai nol.

--------------------

Ketika true, phantom tidak menurunkan garis dasar baris matematika di sekitarnya. Berhubungan dengan atribut OMML m:zeroDesc.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah phantom transparan untuk aturan spasi berbasis kelas.

--------------------

Ketika true, operator dan simbol di dalam phantom tetap memengaruhi spasi matematika di sekitarnya (seperti terlihat). Ketika false, aturan spasi berbasis kelas diabaikan. Berhubungan dengan atribut OMML m:transp.

**Mengembalikan:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah phantom transparan untuk aturan spasi berbasis kelas.

--------------------

Ketika true, operator dan simbol di dalam phantom tetap memengaruhi spasi matematika di sekitarnya (seperti terlihat). Ketika false, aturan spasi berbasis kelas diabaikan. Berhubungan dengan atribut OMML m:transp.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |