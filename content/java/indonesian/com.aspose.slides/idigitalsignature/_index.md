---
title: IDigitalSignature
second_title: Aspose.Slides untuk Referensi API Java
description: Tanda tangan digital dalam file yang ditandatangani.
type: docs
url: /id/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Tanda tangan digital dalam file yang ditandatangani.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objek Sertifikat yang digunakan untuk menandatangani dokumen. |
| [isValid()](#isValid--) | Jika tanda tangan digital ini valid dan dokumen tidak dimanipulasi, nilai ini akan true. |
| [getSignTime()](#getSignTime--) | Waktu saat dokumen ditandatangani. |
| [getComments()](#getComments--) | Tujuan tanda tangan. |
| [setComments(String value)](#setComments-java.lang.String-) | Tujuan tanda tangan. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Objek Sertifikat yang digunakan untuk menandatangani dokumen. Baca-saja byte[].

**Mengembalikan:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
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
public abstract Date getSignTime()
```

Waktu saat dokumen ditandatangani. Baca-saja java.util.Date.

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