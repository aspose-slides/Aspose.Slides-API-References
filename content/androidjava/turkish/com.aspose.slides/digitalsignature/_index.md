---
title: DigitalSignature
second_title: Aspose.Slides for Android Java API Referansı
description: İmzalı dosyada dijital imza.
type: docs
url: /tr/com.aspose.slides/digitalsignature/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

İmzalı dosyada dijital imza.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Presentation örneğini başlat
>  Presentation pres = new Presentation();
>  try {
>     // PFX dosyası ve PFX parolasıyla DigitalSignature nesnesi oluştur
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Yeni dijital imzaya yorum ekle
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Dijital imzayı sunuma ekle
>      pres.getDigitalSignatures().add(signature);
>      // Sunumu kaydet
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Presentation örneğini başlat
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Tüm dijital imzaların geçerli olup olmadığını kontrol et
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

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Belirtilen sertifika ile yeni bir DigitalSignature nesnesi oluşturur. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Belirtilen sertifika dosya yolu ve parola ile yeni bir DigitalSignature nesnesi oluşturur. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getCertificate()](#getCertificate--) | Sertifika nesnesi, belgeyi imzalamak için kullanıldı. |
| [isValid()](#isValid--) | Bu dijital imza geçerli ve belge değiştirilmemişse, bu değer true olacaktır. |
| [getSignTime()](#getSignTime--) | Belgenin imzalandığı zaman. |
| [getComments()](#getComments--) | İmzanın amacı. |
| [setComments(String value)](#setComments-java.lang.String-) | İmzanın amacı. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

Belirtilen sertifika ile yeni bir DigitalSignature nesnesi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| certData | byte[] | sertifikayı içeren bir byte dizisi |
| password | java.lang.String | Sertifikaya erişmek için gereken parola. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

Belirtilen sertifika dosya yolu ve parola ile yeni bir DigitalSignature nesnesi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Sertifika dosyasının yolu. |
| password | java.lang.String | Sertifikaya erişmek için gereken parola. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

Sertifika nesnesi, belgeyi imzalamak için kullanıldı. Salt okunur byte[].

**Döndürür:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```

Bu dijital imza geçerli ve belge değiştirilmemişse, bu değer true olacaktır. Salt okunur boolean.

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


**Döndürür:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

Belgenin imzalandığı zaman. Salt okunur java.util.Date.

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

**Döndürür:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```

İmzanın amacı. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

İmzanın amacı. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |