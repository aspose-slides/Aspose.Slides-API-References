---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili bagian xml khusus.
type: docs
url: /id/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Mewakili bagian xml khusus.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Mengembalikan atau mengatur data xml sebagai string UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Mengembalikan atau mengatur data xml sebagai string UTF-8. |
| [getXmlData()](#getXmlData--) | Mengembalikan atau mengatur data xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Mengembalikan atau mengatur data xml. |
| [getItemId()](#getItemId--) | Menetapkan pengenal unik secara global (GUID) yang secara unik mengidentifikasi satu bagian XML khusus dalam dokumen Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Menetapkan pengenal unik secara global (GUID) yang secara unik mengidentifikasi satu bagian XML khusus dalam dokumen Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Mengembalikan koleksi skema XML yang terkait dengan bagian XML khusus. |
| [remove()](#remove--) | Menghapus bagian xml khusus dari presentasi. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Mengembalikan atau mengatur data xml sebagai string UTF-8. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Mengembalikan atau mengatur data xml sebagai string UTF-8. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Mengembalikan atau mengatur data xml. Baca/tulis byte[].

**Mengembalikan:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Mengembalikan atau mengatur data xml. Baca/tulis byte[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Menetapkan pengenal unik secara global (GUID) yang secara unik mengidentifikasi satu bagian XML khusus dalam dokumen Office Open XML. Hanya-baca java.util.UUID.

**Mengembalikan:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Menetapkan pengenal unik secara global (GUID) yang secara unik mengidentifikasi satu bagian XML khusus dalam dokumen Office Open XML. Hanya-baca java.util.UUID.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Mengembalikan koleksi skema XML yang terkait dengan bagian XML khusus. Hanya-baca String[].

**Mengembalikan:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Menghapus bagian xml khusus dari presentasi.