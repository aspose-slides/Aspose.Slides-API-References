---
title: DigitalSignature
second_title: Aspose.Slides för Android via Java API-referens
description: Digital signatur i signerad fil.
type: docs
url: /sv/com.aspose.slides/digitalsignature/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Digital signatur i signerad fil.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Initiera Presentation-instans
>  Presentation pres = new Presentation();
>  try {
>     // Skapa DigitalSignature-objekt med PFX-fil och PFX-lösenord
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Kommentera ny digital signatur
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Lägg till digital signatur till presentationen
>      pres.getDigitalSignatures().add(signature);
>      // Spara presentationen
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Initiera Presentation-instans
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Kontrollera om alla digitala signaturer är giltiga
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

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Skapar ett nytt DigitalSignature-objekt med det angivna certifikatet. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Skapar ett nytt DigitalSignature-objekt med den angivna sökvägen till certifikatfilen och lösenordet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCertificate()](#getCertificate--) | Certifikatobjekt som användes för att signera dokumentet. |
| [isValid()](#isValid--) | Om denna digitala signatur är giltig och dokumentet inte har manipulerats, kommer detta värde att vara sant. |
| [getSignTime()](#getSignTime--) | Tidpunkten då dokumentet signerades. |
| [getComments()](#getComments--) | Syftet med signaturen. |
| [setComments(String value)](#setComments-java.lang.String-) | Syftet med signaturen. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


Skapar ett nytt DigitalSignature-objekt med det angivna certifikatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certData | byte[] | en bytearray som innehåller certifikatet |
| password | java.lang.String | Lösenord som krävs för att komma åt certifikatet. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


Skapar ett nytt DigitalSignature-objekt med den angivna sökvägen till certifikatfilen och lösenordet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Sökväg till filen med certifikatet. |
| password | java.lang.String | Lösenord som krävs för att komma åt certifikatet. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


Certifikatobjekt som användes för att signera dokumentet. Skrivskyddad byte[].

**Returnerar:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


Om denna digitala signatur är giltig och dokumentet inte har manipulerats, kommer detta värde att vara sant. Skrivskyddad boolean.

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

**Returnerar:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Tidpunkten då dokumentet signerades. Skrivskyddad java.util.Date.

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

**Returnerar:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


Syftet med signaturen. Läs/skriv String.

**Returnerar:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Syftet med signaturen. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |