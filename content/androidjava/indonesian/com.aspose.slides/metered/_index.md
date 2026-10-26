---
title: Metered
second_title: Referensi API Java untuk Aspose.Slides di Android
description: Menyediakan metode untuk mengatur kunci bermeter.
type: docs
url: /id/com.aspose.slides/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Menyediakan metode untuk mengatur kunci bermeter.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Metered()](#Metered--) | Menginisialisasi instance baru dari kelas ini. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Mengatur kunci publik dan privat bermeter. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Mendapatkan ukuran file konsumsi |
| [getConsumptionCredit()](#getConsumptionCredit--) | Mendapatkan kredit konsumsi |
| [isMeteredLicensed()](#isMeteredLicensed--) | Memeriksa apakah bermeter berlisensi |

### Metered() {#Metered--}
```
public Metered()
```

Menginisialisasi instance baru dari kelas ini.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Mengatur kunci publik dan privat bermeter. Jika Anda membeli lisensi bermeter, ketika memulai aplikasi, API ini harus dipanggil; biasanya, ini sudah cukup. Namun, jika selalu gagal mengunggah data konsumsi dan melebihi 24 jam, lisensi akan diatur ke status evaluasi; untuk menghindari hal tersebut, Anda harus secara berkala memeriksa status lisensi, dan jika berada dalam status evaluasi, panggil API ini lagi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| publicKey | java.lang.String | kunci publik |
| privateKey | java.lang.String | kunci privat |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

Mendapatkan ukuran file konsumsi

**Mengembalikan:**
double

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

Mendapatkan kredit konsumsi

**Mengembalikan:**
double - jumlah konsumsi

### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

Memeriksa apakah bermeter berlisensi

**Mengembalikan:**
boolean - Benar atau salah