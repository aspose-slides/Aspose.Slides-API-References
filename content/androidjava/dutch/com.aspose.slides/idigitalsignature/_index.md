---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digitale handtekening in ondertekend bestand.
type: docs
url: /nl/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Digitale handtekening in ondertekend bestand.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCertificate()](#getCertificate--) | Certificate-object dat werd gebruikt om het document te ondertekenen. |
| [isValid()](#isValid--) | Als deze digitale handtekening geldig is en het document niet is gemanipuleerd, zal deze waarde true zijn. |
| [getSignTime()](#getSignTime--) | Het tijdstip waarop het document werd ondertekend. |
| [getComments()](#getComments--) | Het doel van de handtekening. |
| [setComments(String value)](#setComments-java.lang.String-) | Het doel van de handtekening. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```


Certificate-object dat werd gebruikt om het document te ondertekenen. Alleen-lezen byte[].

**Retour:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```


Als deze digitale handtekening geldig is en het document niet is gemanipuleerd, zal deze waarde true zijn. Alleen-lezen boolean.

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

**Retour:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```


Het tijdstip waarop het document werd ondertekend. Alleen-lezen java.util.Date.

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

**Retour:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```


Het doel van de handtekening. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


Het doel van de handtekening. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |