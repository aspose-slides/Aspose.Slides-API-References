---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digital signature in signed file.
type: docs
url: /fr/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Signature numérique dans le fichier signé.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objet certificat utilisé pour signer le document. |
| [isValid()](#isValid--) | Si cette signature numérique est valide et que le document n'a pas été altéré, cette valeur sera vraie. |
| [getSignTime()](#getSignTime--) | Le moment où le document a été signé. |
| [getComments()](#getComments--) | Le but de la signature. |
| [setComments(String value)](#setComments-java.lang.String-) | Le but de la signature. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Objet certificat utilisé pour signer le document. Lecture seule byte[].

**Renvoie :**  
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

Si cette signature numérique est valide et que le document n'a pas été altéré, cette valeur sera vraie. Lecture seule boolean.

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

**Returns:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```

The time when the document was signed. Read-only java.util.Date.

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

**Returns:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

The purpose of signature. Read/write String.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
Le but de la signature. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |