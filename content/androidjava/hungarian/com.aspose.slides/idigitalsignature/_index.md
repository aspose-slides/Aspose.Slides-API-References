---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digitális aláírás aláírt fájlban.
type: docs
url: /hu/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Digitális aláírás aláírt fájlban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCertificate()](#getCertificate--) | A dokumentum aláírásához használt tanúsítványobjektum. |
| [isValid()](#isValid--) | Ha ez a digitális aláírás érvényes, és a dokumentumot nem manipulálták, ez az érték igaz lesz. |
| [getSignTime()](#getSignTime--) | A dokumentum aláírásának időpontja. |
| [getComments()](#getComments--) | Az aláírás célja. |
| [setComments(String value)](#setComments-java.lang.String-) | Az aláírás célja. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```


A dokumentum aláírásához használt tanúsítványobjektum. Csak olvasható byte[].

**Visszatér:**  
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```


Ha ez a digitális aláírás érvényes, és a dokumentumot nem manipulálták, ez az érték igaz lesz. Csak olvasható boolean.

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

**Visszatér:**  
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```


A dokumentum aláírásának időpontja. Csak olvasható java.util.Date.

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

**Visszatér:**  
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```


Az aláírás célja. Olvasható/írható String.

**Visszatér:**  
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


Az aláírás célja. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |