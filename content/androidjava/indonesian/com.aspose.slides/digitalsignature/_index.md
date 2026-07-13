---
title: DigitalSignature
second_title: Referensi API Java Aspose.Slides untuk Android
description: Tanda tangan digital dalam file yang ditandatangani.
type: docs
url: /id/com.aspose.slides/digitalsignature/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Tanda tangan digital dalam file yang ditandatangani.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Inisialisasi instance Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Buat objek DigitalSignature dengan file PFX dan kata sandi PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Berikan komentar pada tanda tangan digital baru
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Tambahkan tanda tangan digital ke presentasi
>      pres.getDigitalSignatures().add(signature);
>      // Simpan presentasi
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Inisialisasi instance Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Periksa apakah semua tanda tangan digital valid
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>              System.out.println(signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>              allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>              System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>              System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Membuat objek DigitalSignature baru dengan sertifikat yang ditentukan. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Membuat objek DigitalSignature baru dengan jalur file sertifikat dan kata sandi yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objek sertifikat yang digunakan untuk menandatangani dokumen. |
| [isValid()](#isValid--) | Jika tanda tangan digital ini valid dan dokumen tidak dimanipulasi, nilai ini akan true. |
| [getSignTime()](#getSignTime--) | Waktu ketika dokumen ditandatangani. |
| [getComments()](#getComments--) | Tujuan tanda tangan. |
| [setComments(String value)](#setComments-java.lang.String-) | Tujuan tanda tangan. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


Membuat objek DigitalSignature baru dengan sertifikat yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| certData | byte[] | array byte yang berisi sertifikat |
| password | java.lang.String | Kata sandi yang diperlukan untuk mengakses sertifikat. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


Membuat objek DigitalSignature baru dengan jalur file sertifikat dan kata sandi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur ke file yang berisi sertifikat. |
| password | java.lang.String | Kata sandi yang diperlukan untuk mengakses sertifikat. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


Objek sertifikat yang digunakan untuk menandatangani dokumen. Baca-saja byte[].

**Mengembalikan:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


Jika tanda tangan digital ini valid dan dokumen tidak dimanipulasi, nilai ini akan true. Baca-saja boolean.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Waktu ketika dokumen ditandatangani. Baca-saja java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


Tujuan tanda tangan. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Tujuan tanda tangan. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |