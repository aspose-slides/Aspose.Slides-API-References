---
title: IProtectionManager
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Manajemen perlindungan kata sandi presentasi.
type: docs
url: /id/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Manajemen perlindungan kata sandi presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Properti ini masuk akal, jika presentasi dilindungi kata sandi. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Properti ini masuk akal, jika presentasi dilindungi kata sandi. |
| [isEncrypted()](#isEncrypted--) | Mendapatkan nilai yang menunjukkan apakah instance ini dienkripsi. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Properti ini masuk akal, jika file presentasi dilindungi kata sandi dan properti dokumen file ini bersifat publik. |
| [isWriteProtected()](#isWriteProtected--) | Mendapatkan nilai yang menunjukkan apakah presentasi ini dilindungi penulisan. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Mengembalikan kata sandi enkripsi. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Mendapatkan atau mengatur rekomendasi hanya-baca. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Mendapatkan atau mengatur rekomendasi hanya-baca. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Mengenkripsi Presentasi dengan kata sandi yang ditentukan. |
| [removeEncryption()](#removeEncryption--) | Menghapus enkripsi. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Menetapkan perlindungan penulisan untuk presentasi ini dengan kata sandi yang ditentukan. |
| [removeWriteProtection()](#removeWriteProtection--) | Menghapus perlindungan penulisan untuk presentasi ini. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Menentukan apakah sebuah presentasi dilindungi kata sandi untuk dimodifikasi. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Properti ini masuk akal, jika presentasi dilindungi kata sandi. Jika true maka properti dokumen dienkripsi dalam file presentasi. Jika false maka properti dokumen bersifat publik sementara presentasi dienkripsi. Boolean baca/tulis.

**Mengembalikan:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Properti ini masuk akal, jika presentasi dilindungi kata sandi. Jika true maka properti dokumen dienkripsi dalam file presentasi. Jika false maka properti dokumen bersifat publik sementara presentasi dienkripsi. Boolean baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Mendapatkan nilai yang menunjukkan apakah instance ini dienkripsi. Boolean hanya-baca.

Value: true if presentation was loaded from encrypted file or \#encrypt(String).encrypt(String) method was called ; otherwise, false.

**Mengembalikan:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Properti ini masuk akal, jika file presentasi dilindungi kata sandi dan properti dokumen file ini bersifat publik. Nilai true berarti hanya properti dokumen yang dimuat dari file presentasi yang dienkripsi tanpa menggunakan kata sandi. Nilai false berarti seluruh presentasi yang dienkripsi dimuat dengan menggunakan kata sandi yang tepat, bukan hanya properti dokumen yang dimuat. Jika presentasi tidak dienkripsi maka nilai properti selalu false. Jika properti dokumen file yang dienkripsi tidak bersifat publik maka nilai properti selalu false. Jika PresentationEx.EncryptDocumentProperties bernilai true maka nilai properti IsOnlyDocumentPropertiesLoaded selalu false. Boolean hanya-baca.

**Mengembalikan:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Mendapatkan nilai yang menunjukkan apakah presentasi ini dilindungi penulisan. Boolean hanya-baca.

**Mengembalikan:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Mengembalikan kata sandi enkripsi. String hanya-baca.

**Mengembalikan:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Mendapatkan atau mengatur rekomendasi hanya-baca. Boolean baca/tulis.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Mengembalikan:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Mendapatkan atau mengatur rekomendasi hanya-baca. Boolean baca/tulis.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Mengenkripsi Presentasi dengan kata sandi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Kata sandi. |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Menghapus enkripsi.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Menetapkan perlindungan penulisan untuk presentasi ini dengan kata sandi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi. |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Menghapus perlindungan penulisan untuk presentasi ini.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi untuk pemeriksaan. |

1. Anda harus memeriksa properti (\#isWriteProtected.isWriteProtected) sebelum memanggil metode ini. 2. Ketika kata sandi bernilai null atau kosong, metode ini mengembalikan false. |

**Mengembalikan:**
boolean - True if the password is valid; otherwise, false.