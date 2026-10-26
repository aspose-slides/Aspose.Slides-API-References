---
title: Storage
second_title: Referensi API Java untuk Aspose.Slides for Android
description: Mewakili penyimpanan data sementara untuk .
type: docs
url: /id/com.aspose.slides/storage/
---
**Warisan:**
java.lang.Object
```
public final class Storage
```

Mewakili penyimpanan data sementara untuk [WebDocument](../../com.aspose.slides/webdocument).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Storage()](#Storage--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Puts the value into the storage. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Gets the data from the storage. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines whether the storage contains an element with the specified key. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Menempatkan nilai ke dalam penyimpanan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | java.lang.String | Kunci untuk nilai. |
| value | TValue | Nilai. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Mendapatkan data dari penyimpanan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | java.lang.String | Kunci nilai. |

**Mengembalikan:**
TValue - Nilai data jika ada dalam koleksi data, null jika tidak.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Menentukan apakah penyimpanan berisi elemen dengan kunci yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | java.lang.String | Kunci nilai. |

**Mengembalikan:**
boolean - True jika penyimpanan berisi elemen dengan kunci yang ditentukan, false jika tidak.