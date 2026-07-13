---
title: ProtectionManager
second_title: Referensi API Java Aspose.Slides untuk Android
description: Manajemen perlindungan kata sandi presentasi.
type: docs
url: /id/com.aspose.slides/protectionmanager/
---
**Pewarisan:**
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
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Properti ini masuk akal bila presentasi dilindungi kata sandi. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Properti ini masuk akal bila presentasi dilindungi kata sandi. |
| [isEncrypted()](#isEncrypted--) | Mengambil nilai yang menunjukkan apakah instansi ini terenkripsi. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Properti ini masuk akal bila file presentasi dilindungi kata sandi dan properti dokumen file ini publik. |
| [isWriteProtected()](#isWriteProtected--) | Mengambil nilai yang menunjukkan apakah presentasi ini dilindungi penulisan. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Mengenkripsi Presentasi dengan kata sandi yang ditentukan. |
| [removeEncryption()](#removeEncryption--) | Menghapus enkripsi. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Mengatur perlindungan penulisan untuk presentasi ini dengan kata sandi yang ditentukan. |
| [removeWriteProtection()](#removeWriteProtection--) | Menghapus perlindungan penulisan untuk presentasi ini. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Menentukan apakah presentasi dilindungi kata sandi untuk dimodifikasi. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Mengambil kata sandi yang digunakan untuk enkripsi presentasi. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Mengambil atau mengatur rekomendasi hanya-baca. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Mengambil atau mengatur rekomendasi hanya-baca. |

### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Properti ini masuk akal bila presentasi dilindungi kata sandi. Jika true maka properti dokumen dienkripsi dalam file presentasi. Jika false maka properti dokumen bersifat publik sementara presentasi terenkripsi. Boolean dapat dibaca/tulis.

**Mengembalikan:**
boolean

### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Properti ini masuk akal bila presentasi dilindungi kata sandi. Jika true maka properti dokumen dienkripsi dalam file presentasi. Jika false maka properti dokumen bersifat publik sementara presentasi terenkripsi. Boolean dapat dibaca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Mengambil nilai yang menunjukkan apakah instansi ini terenkripsi. Boolean hanya-baca.

Nilai: true jika presentasi dimuat dari file terenkripsi atau metode \#encrypt(String).encrypt(String) dipanggil; jika tidak, false.

**Mengembalikan:**
boolean

### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Properti ini masuk akal bila file presentasi dilindungi kata sandi dan properti dokumen file ini publik. Nilai true berarti hanya properti dokumen yang dimuat dari file presentasi terenkripsi tanpa menggunakan kata sandi. Nilai false berarti seluruh presentasi terenkripsi dimuat dengan menggunakan kata sandi yang benar, bukan hanya properti dokumen yang dimuat. Jika presentasi tidak terenkripsi maka nilai properti selalu false. Jika properti dokumen dari file terenkripsi tidak publik maka nilai properti selalu false. Jika Presentation.EncryptDocumentProperties bernilai true maka nilai properti IsOnlyDocumentPropertiesLoaded selalu false. Boolean hanya-baca.

**Mengembalikan:**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Mengambil nilai yang menunjukkan apakah presentasi ini dilindungi penulisan. Boolean hanya-baca.

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
| Parameter | Tipe | Deskripsi |
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

Mengatur perlindungan penulisan untuk presentasi ini dengan kata sandi yang ditentukan.

--------------------

> ```
> The following sample code shows you how to set a write protection to a presentation.
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi. |

### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Menghapus perlindungan penulisan untuk presentasi ini.

--------------------

> ```
> Contoh kode ini menunjukkan cara menghapus perlindungan penulisan dari presentasi PowerPoint.
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

Menentukan apakah presentasi dilindungi kata sandi untuk dimodifikasi.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi untuk pemeriksaan. |

1. Anda harus memeriksa properti (\#isWriteProtected.isWriteProtected) sebelum memanggil metode ini. 2. Ketika kata sandi bernilai null atau kosong, metode ini mengembalikan false. |

**Mengembalikan:**
boolean - True jika kata sandi valid; jika tidak, false.

### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Mengambil kata sandi yang digunakan untuk enkripsi presentasi. String hanya-baca.

**Mengembalikan:**
java.lang.String

### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Mengambil atau mengatur rekomendasi hanya-baca. Boolean dapat dibaca/tulis.

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

Mengambil atau mengatur rekomendasi hanya-baca. Boolean dapat dibaca/tulis.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |