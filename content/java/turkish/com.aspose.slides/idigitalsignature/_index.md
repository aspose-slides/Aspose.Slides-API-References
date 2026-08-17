---
title: IDigitalSignature
second_title: Aspose.Slides for Java API Reference
description: İmzalı dosyada dijital imza.
type: docs
url: /tr/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

İmzalı dosyada dijital imza.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCertificate()](#getCertificate--) | Belgeyi imzalamak için kullanılan sertifika nesnesi. |
| [isValid()](#isValid--) | Bu dijital imza geçerli ve belgeye müdahale edilmemişse, bu değer true olur. |
| [getSignTime()](#getSignTime--) | Belgenin imzalandığı zaman. |
| [getComments()](#getComments--) | İmzanın amacı. |
| [setComments(String value)](#setComments-java.lang.String-) | İmzanın amacı. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Belgeyi imzalamak için kullanılan sertifika nesnesi. Salt-okunur byte[].

**Döndürür:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

Bu dijital imza geçerli ve belgeye müdahale edilmemişse, bu değer true olur. Salt-okunur boolean.

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
public abstract Date getSignTime()
```

Belgenin imzalandığı zaman. Salt-okunur java.util.Date.

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


**Döndürür:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

İmzanın amacı. Okunur/yazılabilir String.

**Döndürür:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

İmzanın amacı. Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |