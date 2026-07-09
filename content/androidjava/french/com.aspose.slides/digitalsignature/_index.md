---
title: DigitalSignature
second_title: Référence API Aspose.Slides pour Android via Java
description: Signature numérique dans le fichier signé.
type: docs
url: /fr/com.aspose.slides/digitalsignature/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Signature numérique dans le fichier signé.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Initialiser l'instance Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Créer un objet DigitalSignature avec le fichier PFX et le mot de passe PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Commenter la nouvelle signature numérique
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Ajouter la signature numérique à la présentation
>      pres.getDigitalSignatures().add(signature);
>      // Enregistrer la présentation
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Initialiser l'instance Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Vérifier si toutes les signatures numériques sont valides
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
## Constructors

| Constructor | Description |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Creates a new DigitalSignature object with the specified certificate. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Creates a new DigitalSignature object with the specified certificate file path and password. |
## Methods

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | Certificate object that was used to sign the document. |
| [isValid()](#isValid--) | If this digital signature is valid and the document has not been tampered with, this value will be true. |
| [getSignTime()](#getSignTime--) | The time when the document was signed. |
| [getComments()](#getComments--) | The purpose of signature. |
| [setComments(String value)](#setComments-java.lang.String-) | The purpose of signature. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

Creates a new DigitalSignature object with the specified certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certData | byte[] | a byte array containing the certificate |
| password | java.lang.String | Password required to access certificate. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

Creates a new DigitalSignature object with the specified certificate file path and password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Path to the file with certificate. |
| password | java.lang.String | Password required to access certificate. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

Certificate object that was used to sign the document. Read-only byte[].

**Returns:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```

If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only boolean.

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
public final Date getSignTime()
```

The time when the document was signed. Read-only java.util.Date.

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

**Returns:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```

The purpose of signature. Read/write String.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)

Le but de la signature. Lecture/écriture String.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |