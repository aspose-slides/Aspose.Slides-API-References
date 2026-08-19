---
title: ProtectionManager
second_title: Referensi API Aspose.Slides untuk Java
description: Manajemen perlindungan kata sandi presentasi.
type: docs
url: /id/com.aspose.slides/protectionmanager/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Manajemen perlindungan kata sandi presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Properti ini masuk akal, jika presentasi dilindungi kata sandi. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Properti ini masuk akal, jika presentasi dilindungi kata sandi. |
| [isEncrypted()](#isEncrypted--) | Mendapatkan nilai yang menunjukkan apakah instance ini dienkripsi. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Properti ini masuk akal, jika file presentasi dilindungi kata sandi dan properti dokumen dari file ini bersifat publik. |
| [isWriteProtected()](#isWriteProtected--) | Mendapatkan nilai yang menunjukkan apakah presentasi ini dilindungi tulis. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Mengenkripsi Presentasi dengan kata sandi yang ditentukan. |
| [removeEncryption()](#removeEncryption--) | Menghapus enkripsi. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Mengatur perlindungan tulis untuk presentasi ini dengan kata sandi yang ditentukan. |
| [removeWriteProtection()](#removeWriteProtection--) | Menghapus perlindungan tulis untuk presentasi ini. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Menentukan apakah sebuah presentasi dilindungi kata sandi untuk dimodifikasi. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Mendapatkan kata sandi yang digunakan untuk enkripsi presentasi. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Mendapatkan atau mengatur rekomendasi baca-saja. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Mendapatkan atau mengatur rekomendasi baca-saja. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```


Properti ini masuk akal, jika presentasi dilindungi kata sandi. Jika true maka properti dokumen dienkripsi dalam file presentasi. Jika false maka properti dokumen bersifat publik sementara presentasi dienkripsi. Boolean baca/tulis.

**Mengembalikan:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```


Properti ini masuk akal, jika presentasi dilindungi kata sandi. Jika true maka properti dokumen dienkripsi dalam file presentasi. Jika false maka properti dokumen bersifat publik sementara presentasi dienkripsi. Boolean baca/tulis.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Mendapatkan nilai yang menunjukkan apakah instance ini dienkripsi. Boolean baca-saja.

Nilai: true jika presentasi dimuat dari file terenkripsi atau \#encrypt(String).encrypt(String) method dipanggil ; otherwise, false.

**Mengembalikan:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```


Properti ini masuk akal, jika file presentasi dilindungi kata sandi dan properti dokumen dari file ini bersifat publik. Nilai true berarti hanya properti dokumen yang dimuat dari file presentasi terenkripsi tanpa penggunaan kata sandi. Nilai false berarti seluruh presentasi terenkripsi dimuat dengan penggunaan kata sandi yang benar, tidak hanya properti dokumen yang dimuat. Jika presentasi tidak terenkripsi maka nilai properti selalu false. Jika properti dokumen dari file terenkripsi tidak bersifat publik maka nilai properti selalu false. Jika Presentation.EncryptDocumentProperties true maka nilai properti IsOnlyDocumentPropertiesLoaded selalu false. Boolean baca-saja.

**Mengembalikan:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```


Mendapatkan nilai yang menunjukkan apakah presentasi ini dilindungi tulis. Boolean baca-saja.

**Mengembalikan:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```


Mengenkripsi Presentasi dengan kata sandi yang ditentukan.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Kata sandi. |

### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```


Menghapus enkripsi.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


Mengatur perlindungan tulis untuk presentasi ini dengan kata sandi yang ditentukan.

--------------------

> ```
> Berikut ini contoh kode yang menunjukkan cara mengatur perlindungan tulis pada sebuah presentasi.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi. |

### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```


Menghapus perlindungan tulis untuk presentasi ini.

--------------------

> ```
> Contoh kode ini menunjukkan cara menghapus perlindungan tulis dari sebuah Presentasi PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


Menentukan apakah sebuah presentasi dilindungi kata sandi untuk dimodifikasi.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi untuk pengecekan.

--------------------

1. Anda harus memeriksa properti (\#isWriteProtected.isWriteProtected) sebelum memanggil metode ini. 2. Ketika kata sandi null atau kosong, metode ini mengembalikan false. |

**Mengembalikan:**
boolean - True jika kata sandi valid; otherwise, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```


Mendapatkan kata sandi yang digunakan untuk enkripsi presentasi. String baca-saja.

**Mengembalikan:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```


Mendapatkan atau mengatur rekomendasi baca-saja. Boolean baca/tulis.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```


Mendapatkan atau mengatur rekomendasi baca-saja. Boolean baca/tulis.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | boolean |  |