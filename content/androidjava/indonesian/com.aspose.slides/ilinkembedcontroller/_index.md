---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /id/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Antarmuka callback yang digunakan untuk menentukan bagaimana objek harus diproses selama penyimpanan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Menentukan dimana objek harus disimpan. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Mengembalikan sebuah URL ke objek eksternal. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Menyimpan objek eksternal. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Menentukan dimana objek harus disimpan. Metode ini dipanggil sekali untuk setiap id objek. Tidak dijamin tidak akan ada dua objek dengan data, semanticName, dan contentType yang sama tetapi dengan id yang berbeda.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | int | Id objek. Id ini unik untuk seluruh operasi penyimpanan. |
| entityData | byte[] | Data biner objek. Parameter ini dapat bernilai null, jika data biner objek belum dihasilkan. |
| semanticName | java.lang.String | Beberapa teks pendek yang menjelaskan makna objek. Kontroler dapat menggunakan ini sebagai bagian dari nama objek eksternal, namun tergantung pada dispatcher untuk memastikan nama tersebut unik dan hanya berisi karakter yang diizinkan. |
| contentType | java.lang.String | Tipe MIME objek. |
| recomendedExtension | java.lang.String | Ekstensi nama file yang direkomendasikan untuk tipe MIME ini. |

**Mengembalikan:**
int - Keputusan
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Mengembalikan sebuah URL ke objek eksternal. Metode ini selalu dipanggil jika #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) mengembalikan [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) dan dapat dipanggil jika #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) mengembalikan [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) tetapi penyematan tidak memungkinkan. Dapat dipanggil berkali-kali untuk id objek yang sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | int | Id objek. Id ini unik untuk seluruh operasi penyimpanan. |
| referrer | int | Id objek yang merujuk atau 0, jika objek dirujuk oleh dokumen akar. Dapat digunakan untuk menghasilkan tautan relatif. |

**Mengembalikan:**
java.lang.String - URL objek eksternal atau null jika objek ini harus diabaikan.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Menyimpan objek eksternal.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | int | Id objek. Id ini unik untuk seluruh operasi penyimpanan. |
| entityData | byte[] | Data biner objek. Parameter ini tidak boleh bernilai null. |