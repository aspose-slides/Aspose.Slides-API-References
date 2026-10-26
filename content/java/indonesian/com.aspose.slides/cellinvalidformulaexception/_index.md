---
title: CellInvalidFormulaException
second_title: Referensi API Aspose.Slides untuk Java
description: Pengecualian yang dilemparkan ketika rumus yang dihitung tidak benar atau tidak dapat diparse.
type: docs
url: /id/com.aspose.slides/cellinvalidformulaexception/
---
**Pewarisan:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Pengecualian yang dilemparkan ketika rumus yang dihitung tidak benar atau tidak dapat diparse.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Menginisialisasi sebuah instance baru dari kelas [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) dengan pesan error yang ditentukan. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Menginisialisasi sebuah instance baru dari kelas [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) dengan pesan error yang ditentukan dan referensi ke pengecualian internal yang menjadi penyebab pengecualian ini. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) dengan pesan error yang ditentukan dan referensi sel yang berisi formula tidak valid. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getReference()](#getReference--) | Mendapatkan referensi sel yang berisi formula tidak valid. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Menginisialisasi sebuah instance baru dari kelas [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Menginisialisasi sebuah instance baru dari kelas [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) dengan pesan error yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | String yang menggambarkan kesalahan. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Menginisialisasi sebuah instance baru dari kelas [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) dengan pesan error yang ditentukan dan referensi ke pengecualian internal yang menjadi penyebab pengecualian ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | String yang menggambarkan kesalahan. |
| innerException | java.lang.RuntimeException | Pengecualian yang menjadi penyebab pengecualian saat ini. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Menginisialisasi sebuah instance baru dari kelas [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) dengan pesan error yang ditentukan dan referensi sel yang berisi formula tidak valid.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | String yang menggambarkan kesalahan. |
| reference | java.lang.String | String yang menggambarkan referensi ke pengecualian internal |

### getReference() {#getReference--}
```
public final String getReference()
```

Mendapatkan referensi sel yang berisi formula tidak valid.

**Mengembalikan:**
java.lang.String