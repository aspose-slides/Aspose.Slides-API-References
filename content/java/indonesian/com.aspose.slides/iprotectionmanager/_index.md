---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
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
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Properti ini masuk akal jika presentasi dilindungi kata sandi. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Properti ini masuk akal jika presentasi dilindungi kata sandi. |
| [isEncrypted()](#isEncrypted--) | Mengambil nilai yang menunjukkan apakah instance ini dienkripsi. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Properti ini masuk akal jika file presentasi dilindungi kata sandi dan properti dokumen file ini bersifat publik. |
| [isWriteProtected()](#isWriteProtected--) | Mengambil nilai yang menunjukkan apakah presentasi ini dilindungi penulisan. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Mengembalikan kata sandi enkripsi. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Mengambil atau mengatur rekomendasi hanya-baca. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Mengambil atau mengatur rekomendasi hanya-baca. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Mengenkripsi Presentasi dengan kata sandi yang ditentukan. |
| [removeEncryption()](#removeEncryption--) | Menghapus enkripsi. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Mengatur perlindungan penulisan untuk presentasi ini dengan kata sandi yang ditentukan. |
| [removeWriteProtection()](#removeWriteProtection--) | Menghapus perlindungan penulisan untuk presentasi ini. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Menentukan apakah sebuah presentasi dilindungi kata sandi untuk dimodifikasi. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Properti ini masuk akal jika presentasi dilindungi kata sandi. Jika true maka properti dokumen dienkripsi dalam file presentasi. Jika false maka properti dokumen bersifat publik sementara presentasi dienkripsi. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Properti ini masuk akal jika presentasi dilindungi kata sandi. Jika true maka properti dokumen dienkripsi dalam file presentasi. Jika false maka properti dokumen bersifat publik sementara presentasi dienkripsi. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Mengambil nilai yang menunjukkan apakah instance ini dienkripsi. Baca-saja boolean.

Nilai: true jika presentasi dimuat dari file terenkripsi atau metode \#encrypt(String).encrypt(String) dipanggil; selain itu, false.

**Mengembalikan:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Properti ini masuk akal jika file presentasi dilindungi kata sandi dan properti dokumen file ini bersifat publik. Nilai true berarti hanya properti dokumen yang dimuat dari file presentasi terenkripsi tanpa menggunakan kata sandi. Nilai false berarti seluruh presentasi terenkripsi dimuat dengan menggunakan kata sandi yang benar, bukan hanya properti dokumen yang dimuat. Jika presentasi tidak terenkripsi maka nilai properti selalu false. Jika properti dokumen dari file terenkripsi tidak bersifat publik maka nilai properti selalu false. Jika PresentationEx.EncryptDocumentProperties bernilai true maka nilai properti IsOnlyDocumentPropertiesLoaded selalu false. Baca-saja boolean.

**Mengembalikan:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Mengambil nilai yang menunjukkan apakah presentasi ini dilindungi penulisan. Baca-saja boolean.

**Mengembalikan:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Mengembalikan kata sandi enkripsi. String baca-saja.

**Mengembalikan:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Mengambil atau mengatur rekomendasi hanya-baca. Baca/tulis boolean.

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

Mengambil atau mengatur rekomendasi hanya-baca. Baca/tulis boolean.

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
| encryptionPassword | java.lang.String | Kata sandinya. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Menghapus enkripsi.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Mengatur perlindungan penulisan untuk presentasi ini dengan kata sandi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandinya. |
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
| password | java.lang.String | Kata sandi untuk pemeriksaan.

--------------------

1. Anda harus memeriksa properti (\#isWriteProtected.isWriteProtected) sebelum memanggil metode ini. 2. Ketika kata sandi null atau kosong, metode ini mengembalikan false. |

**Mengembalikan:**
boolean - true jika kata sandi valid; selain itu, false.