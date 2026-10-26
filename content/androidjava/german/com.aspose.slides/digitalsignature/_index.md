---
title: DigitalSignature
second_title: Aspose.Slides für Android über Java API Referenz
description: Digitale Signatur in signierter Datei.
type: docs
url: /de/com.aspose.slides/digitalsignature/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Digitale Signatur in signierter Datei.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Präsentationsinstanz initialisieren
>  Presentation pres = new Presentation();
>  try {
>     // DigitalSignature-Objekt mit PFX-Datei und PFX-Passwort erstellen
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Neue digitale Signatur kommentieren
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Digitale Signatur zur Präsentation hinzufügen
>      pres.getDigitalSignatures().add(signature);
>      // Präsentation speichern
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Präsentationsinstanz initialisieren
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Überprüfen, ob alle digitalen Signaturen gültig sind
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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Erstellt ein neues DigitalSignature-Objekt mit dem angegebenen Zertifikat. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Erstellt ein neues DigitalSignature-Objekt mit dem angegebenen Zertifikatdateipfad und Passwort. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCertificate()](#getCertificate--) | Zertifikatsobjekt, das zum Signieren des Dokuments verwendet wurde. |
| [isValid()](#isValid--) | Wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde, ist dieser Wert wahr. |
| [getSignTime()](#getSignTime--) | Der Zeitpunkt, zu dem das Dokument signiert wurde. |
| [getComments()](#getComments--) | Der Zweck der Signatur. |
| [setComments(String value)](#setComments-java.lang.String-) | Der Zweck der Signatur. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

Erstellt ein neues DigitalSignature-Objekt mit dem angegebenen Zertifikat.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certData | byte[] | ein Byte-Array, das das Zertifikat enthält |
| password | java.lang.String | Passwort, das zum Zugriff auf das Zertifikat erforderlich ist. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

Erstellt ein neues DigitalSignature-Objekt mit dem angegebenen Zertifikatdateipfad und Passwort.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Pfad zur Datei mit dem Zertifikat. |
| password | java.lang.String | Passwort, das zum Zugriff auf das Zertifikat erforderlich ist. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

Zertifikatsobjekt, das zum Signieren des Dokuments verwendet wurde. Nur lesbar byte[].

**Rückgabewert:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```

Wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde, ist dieser Wert wahr. Nur lesbar boolean.

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

**Rückgabewert:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

Der Zeitpunkt, zu dem das Dokument signiert wurde. Nur lesbar java.util.Date.

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

**Rückgabewert:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```

Der Zweck der Signatur. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Der Zweck der Signatur. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |