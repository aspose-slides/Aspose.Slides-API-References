---
title: CellCircularReferenceException
second_title: Aspose.Slides untuk Referensi API Java
description: Pengecualian yang dilemparkan ketika satu atau lebih referensi siklik terdeteksi di mana sebuah formula merujuk ke selnya sendiri secara langsung atau tidak langsung.
type: docs
url: /id/com.aspose.slides/cellcircularreferenceexception/
---
**Pewarisan:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Pengecualian yang dilemparkan ketika satu atau lebih referensi siklik terdeteksi di mana sebuah formula merujuk ke selnya sendiri secara langsung atau tidak langsung.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Menginisialisasi instance baru dari kelas [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Menginisialisasi instance baru dari kelas [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) dengan pesan error yang ditentukan. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Menginisialisasi instance baru dari kelas [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) dengan pesan error yang ditentukan dan referensi ke inner exception yang menjadi penyebab pengecualian ini. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) dengan pesan error yang ditentukan dan referensi sel siklik. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getReference()](#getReference--) | Mendapatkan referensi sel siklik. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Menginisialisasi instance baru dari kelas [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).
### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Menginisialisasi instance baru dari kelas [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) dengan pesan error yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | Sebuah string yang menjelaskan kesalahan. |
### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Menginisialisasi instance baru dari kelas [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) dengan pesan error yang ditentukan dan referensi ke inner exception yang menjadi penyebab pengecualian ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | Sebuah string yang menjelaskan kesalahan. |
| innerException | java.lang.RuntimeException | Pengecualian yang menjadi penyebab pengecualian saat ini. |
### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Menginisialisasi instance baru dari kelas [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) dengan pesan error yang ditentukan dan referensi sel siklik.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | Sebuah string yang menjelaskan kesalahan. |
| reference | java.lang.String | Sebuah referensi sel siklik. |
### getReference() {#getReference--}
```
public final String getReference()
```

Mendapatkan referensi sel siklik.

**Mengembalikan:**
java.lang.String