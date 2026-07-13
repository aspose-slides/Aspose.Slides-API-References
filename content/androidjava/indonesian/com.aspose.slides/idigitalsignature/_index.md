---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digital signature in signed file.
type: docs
url: /id/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Tanda tangan digital dalam file yang ditandatangani.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objek sertifikat yang digunakan untuk menandatangani dokumen. |
| [isValid()](#isValid--) | Jika tanda tangan digital ini valid dan dokumen tidak diubah, nilai ini akan bernilai true. |
| [getSignTime()](#getSignTime--) | Waktu ketika dokumen ditandatangani. |
| [getComments()](#getComments--) | Tujuan tanda tangan. |
| [setComments(String value)](#setComments-java.lang.String-) | Tujuan tanda tangan. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```


Objek sertifikat yang digunakan untuk menandatangani dokumen. Hanya-baca byte[].

**Mengembalikan:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```


Jika tanda tangan digital ini valid dan dokumen tidak diubah, nilai ini akan bernilai true. Hanya-baca boolean.

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
public abstract Date getSignTime()
```


Waktu ketika dokumen ditandatangani. Hanya-baca java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.IsValid ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```


Tujuan tanda tangan. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


Tujuan tanda tangan. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |