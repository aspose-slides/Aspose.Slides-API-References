---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digital signature in signed file.
type: docs
url: /it/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Firma digitale in file firmato.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCertificate()](#getCertificate--) | Oggetto Certificate utilizzato per firmare il documento. |
| [isValid()](#isValid--) | Se questa firma digitale è valida e il documento non è stato manomesso, questo valore sarà true. |
| [getSignTime()](#getSignTime--) | Il momento in cui il documento è stato firmato. |
| [getComments()](#getComments--) | Lo scopo della firma. |
| [setComments(String value)](#setComments-java.lang.String-) | Lo scopo della firma. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```


Oggetto Certificate utilizzato per firmare il documento. Solo lettura byte[].

**Restituisce:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```


Se questa firma digitale è valida e il documento non è stato manomesso, questo valore sarà true. Solo lettura boolean.

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

**Restituisce:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```


Il momento in cui il documento è stato firmato. Solo lettura java.util.Date.

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

**Restituisce:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```


Lo scopo della firma. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


Lo scopo della firma. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |