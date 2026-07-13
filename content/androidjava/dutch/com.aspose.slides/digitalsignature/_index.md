---
title: DigitalSignature
second_title: Aspose.Slides voor Android via Java API-referentie
description: Digitale handtekening in ondertekend bestand.
type: docs
url: /nl/com.aspose.slides/digitalsignature/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Digitale handtekening in ondertekend bestand.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Initialiseer Presentation-instantie
>  Presentation pres = new Presentation();
>  try {
>     // Maak DigitalSignature-object met PFX-bestand en PFX-wachtwoord
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Commentaar bij nieuwe digitale handtekening
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Voeg digitale handtekening toe aan presentatie
>      pres.getDigitalSignatures().add(signature);
>      // Sla presentatie op
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Initialiseer Presentation-instantie
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Controleer of alle digitale handtekeningen geldig zijn
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

## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Maakt een nieuw DigitalSignature-object met het opgegeven certificaat. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Maakt een nieuw DigitalSignature-object met het opgegeven certificaatbestandspad en wachtwoord. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCertificate()](#getCertificate--) | Certificaatobject dat is gebruikt om het document te ondertekenen. |
| [isValid()](#isValid--) | Als deze digitale handtekening geldig is en het document niet is gemanipuleerd, zal deze waarde true zijn. |
| [getSignTime()](#getSignTime--) | Het tijdstip waarop het document is ondertekend. |
| [getComments()](#getComments--) | Het doel van de handtekening. |
| [setComments(String value)](#setComments-java.lang.String-) | Het doel van de handtekening. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


Maakt een nieuw DigitalSignature-object met het opgegeven certificaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| certData | byte[] | een byte-array die het certificaat bevat |
| password | java.lang.String | Wachtwoord vereist om toegang te krijgen tot het certificaat. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


Maakt een nieuw DigitalSignature-object met het opgegeven certificaatbestandspad en wachtwoord.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Pad naar het bestand met certificaat. |
| password | java.lang.String | Wachtwoord vereist om toegang te krijgen tot het certificaat. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


Certificaatobject dat is gebruikt om het document te ondertekenen. Alleen-lezen byte[].

**Retour:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
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
public final Date getSignTime()
```


Het tijdstip waarop het document is ondertekend. Alleen-lezen java.util.Date.

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

**Retour:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


Het doel van de handtekening. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Het doel van de handtekening. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |