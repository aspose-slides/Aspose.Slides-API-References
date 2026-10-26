---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Firma digital en archivo firmado.
type: docs
url: /es/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Firma digital en archivo firmado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objeto de certificado que se utilizó para firmar el documento. |
| [isValid()](#isValid--) | Si esta firma digital es válida y el documento no ha sido alterado, este valor será true. |
| [getSignTime()](#getSignTime--) | El momento en que el documento fue firmado. |
| [getComments()](#getComments--) | El propósito de la firma. |
| [setComments(String value)](#setComments-java.lang.String-) | El propósito de la firma. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Objeto de certificado que se utilizó para firmar el documento. Solo lectura byte[].

**Devuelve:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

Si esta firma digital es válida y el documento no ha sido alterado, este valor será true. Solo lectura boolean.

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

**Devuelve:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```

El momento en que el documento fue firmado. Solo lectura java.util.Date.

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

**Devuelve:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

El propósito de la firma. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

El propósito de la firma. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |