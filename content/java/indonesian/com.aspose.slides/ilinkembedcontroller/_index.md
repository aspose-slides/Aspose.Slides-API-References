---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /id/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Antarmuka callback yang digunakan untuk menentukan bagaimana objek diproses selama penyimpanan.
## Metode

| Method | Description |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Determines where object should be stored. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Returns an URL to an external object. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Saves external object. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Menentukan di mana objek harus disimpan. Metode ini dipanggil satu kali untuk setiap id objek. Tidak dijamin bahwa tidak akan ada dua objek dengan data, semanticName, dan contentType yang sama tetapi dengan id yang berbeda.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | int | Id objek. Id ini unik untuk seluruh operasi penyimpanan. |
| entityData | byte[] | Data biner objek. Parameter ini dapat null, jika data biner objek belum dihasilkan. |
| semanticName | java.lang.String | Beberapa teks pendek yang menggambarkan makna objek. Kontroler dapat menggunakan ini sebagai bagian dari nama objek eksternal, tetapi terserah dispatcher untuk memastikan bahwa nama-nama tersebut unik dan hanya berisi karakter yang diizinkan. |
| contentType | java.lang.String | Tipe MIME objek. |
| recomendedExtension | java.lang.String | Ekstensi nama file, yang direkomendasikan untuk tipe MIME ini. |

**Mengembalikan:**
int - Keputusan
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Mengembalikan sebuah URL ke objek eksternal. Metode ini selalu dipanggil jika \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) mengembalikan [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) dan dapat dipanggil jika \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) mengembalikan [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) tetapi penyematan tidak mungkin. Dapat dipanggil beberapa kali untuk id objek yang sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | int | Id objek. Id ini unik untuk seluruh operasi penyimpanan. |
| referrer | int | Id objek yang merujuk atau 0, jika objek dirujuk oleh dokumen root. Dapat digunakan untuk menghasilkan tautan relatif. |

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
| entityData | byte[] | Data biner objek. Parameter ini tidak boleh null. |