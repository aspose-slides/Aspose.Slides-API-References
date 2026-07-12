---
title: IDigitalSignature
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: İmzalı dosyadaki dijital imza.
type: docs
url: /tr/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

İmzalı dosyadaki dijital imza.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCertificate()](#getCertificate--) | Belgeyi imzalamak için kullanılan sertifika nesnesi. |
| [isValid()](#isValid--) | Bu dijital imza geçerliyse ve belge değiştirilmemişse, bu değer doğru olacaktır. |
| [getSignTime()](#getSignTime--) | Belgenin imzalanma zamanı. |
| [getComments()](#getComments--) | İmzanın amacı. |
| [setComments(String value)](#setComments-java.lang.String-) | İmzanın amacı. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Sertifika nesnesi, belgeyi imzalamak için kullanıldı. Yalnızca okunabilir byte[].

**Döndürür:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

Bu dijital imza geçerliyse ve belge değiştirilmemişse, bu değer doğru olacaktır. Yalnızca okunabilir boolean.

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
public abstract Date getSignTime()
```

Belgenin imzalanma zamanı. Yalnızca okunabilir java.util.Date.

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

**Döndürür:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

İmzanın amacı. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

İmzanın amacı. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |