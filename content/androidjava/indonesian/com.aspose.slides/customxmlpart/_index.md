---
title: CustomXmlPart
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili bagian XML khusus.
type: docs
url: /id/com.aspose.slides/customxmlpart/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Mewakili bagian XML khusus.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getXmlData()](#getXmlData--) | Mengembalikan atau mengatur data xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Mengembalikan atau mengatur data xml. |
| [getXmlAsString()](#getXmlAsString--) | Mengembalikan atau mengatur data xml sebagai string UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Mengembalikan atau mengatur data xml sebagai string UTF-8. |
| [getItemId()](#getItemId--) | Menentukan pengenal unik secara global (GUID) yang secara unik mengidentifikasi satu bagian XML khusus dalam dokumen Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Menentukan pengenal unik secara global (GUID) yang secara unik mengidentifikasi satu bagian XML khusus dalam dokumen Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Mengembalikan kumpulan skema XML yang terkait dengan bagian XML khusus. |
| [remove()](#remove--) | Menghapus bagian XML khusus dari presentasi. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


Mengembalikan atau mengatur data xml. Baca/tulis byte[].

**Mengembalikan:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


Mengembalikan atau mengatur data xml. Baca/tulis byte[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


Mengembalikan atau mengatur data xml sebagai string UTF-8. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


Mengembalikan atau mengatur data xml sebagai string UTF-8. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Menentukan pengenal unik secara global (GUID) yang secara unik mengidentifikasi satu bagian XML khusus dalam dokumen Office Open XML. Baca-saja java.util.UUID.

**Mengembalikan:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Menentukan pengenal unik secara global (GUID) yang secara unik mengidentifikasi satu bagian XML khusus dalam dokumen Office Open XML. Baca-saja java.util.UUID.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Mengembalikan kumpulan skema XML yang terkait dengan bagian XML khusus. Baca-saja String[].

**Mengembalikan:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Menghapus bagian XML khusus dari presentasi.