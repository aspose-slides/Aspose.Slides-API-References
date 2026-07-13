---
title: CellInvalidReferenceException
second_title: Referensi API Java Aspose.Slides untuk Android
description: Pengecualian yang dilemparkan ketika referensi sel yang tidak valid ditemui.
type: docs
url: /id/com.aspose.slides/cellinvalidreferenceexception/
---
**Pewarisan:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Pengecualian yang dilemparkan ketika referensi sel yang tidak valid ditemui.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Menginisialisasi sebuah instance baru dari kelas [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) dengan pesan kesalahan yang ditentukan. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Menginisialisasi sebuah instance baru dari kelas [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) dengan pesan kesalahan yang ditentukan dan referensi ke pengecualian internal yang menjadi penyebab pengecualian ini. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) dengan pesan kesalahan yang ditentukan dan referensi sel yang tidak valid. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getReference()](#getReference--) | Mengambil referensi sel yang tidak valid. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

Menginisialisasi sebuah instance baru dari kelas [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

Menginisialisasi sebuah instance baru dari kelas [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) dengan pesan kesalahan yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | String yang menjelaskan kesalahan. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

Menginisialisasi sebuah instance baru dari kelas [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) dengan pesan kesalahan yang ditentukan dan referensi ke pengecualian internal yang menjadi penyebab pengecualian ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | String yang menjelaskan kesalahan. |
| innerException | java.lang.RuntimeException | Pengecualian yang menjadi penyebab pengecualian saat ini. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

Menginisialisasi sebuah instance baru dari kelas [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) dengan pesan kesalahan yang ditentukan dan referensi sel yang tidak valid.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | String yang menjelaskan kesalahan. |
| reference | java.lang.String | Referensi sel yang tidak valid. |

### getReference() {#getReference--}
```
public final String getReference()
```

Mengambil referensi sel yang tidak valid.

**Mengembalikan:**
java.lang.String