---
title: DigitalSignature
second_title: Référence de l'API Aspose.Slides pour Java
description: Signature numérique dans le fichier signé.
type: docs
url: /fr/com.aspose.slides/digitalsignature/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Signature numérique dans le fichier signé.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Initialise l'instance Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Crée l'objet DigitalSignature avec le fichier PFX et le mot de passe PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Commenter la nouvelle signature numérique
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Ajoutez la signature numérique à la présentation
>      pres.getDigitalSignatures().add(signature);
>      // Enregistrez la présentation
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Initialise l'instance Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Vérifiez si toutes les signatures numériques sont valides
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

## Constructeurs

| Constructor | Description |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Crée un nouvel objet DigitalSignature avec le certificat spécifié. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Crée un nouvel objet DigitalSignature avec le chemin du fichier de certificat spécifié et le mot de passe. |
## Méthodes

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objet certificat qui a été utilisé pour signer le document. |
| [isValid()](#isValid--) | Si cette signature numérique est valide et que le document n’a pas été altéré, cette valeur sera vraie. |
| [getSignTime()](#getSignTime--) | Le moment où le document a été signé. |
| [getComments()](#getComments--) | Le but de la signature. |
| [setComments(String value)](#setComments-java.lang.String-) | Le but de la signature. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


Crée un nouvel objet DigitalSignature avec le certificat spécifié.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| certData | byte[] | un tableau d’octets contenant le certificat |
| password | java.lang.String | Mot de passe requis pour accéder au certificat. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


Crée un nouvel objet DigitalSignature avec le chemin du fichier de certificat spécifié et le mot de passe.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Chemin vers le fichier contenant le certificat. |
| password | java.lang.String | Mot de passe requis pour accéder au certificat. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


Objet certificat qui a été utilisé pour signer le document. Lecture seule byte[].

**Retourne :**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


Si cette signature numérique est valide et que le document n’a pas été altéré, cette valeur sera vraie. Lecture seule boolean.

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

**Retourne :**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Le moment où le document a été signé. Lecture seule java.util.Date.

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

**Retourne :**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


Le but de la signature. Lecture/écriture String.

**Retourne :**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Le but de la signature. Lecture/écriture String.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |