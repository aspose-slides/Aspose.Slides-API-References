---
title: DigitalSignature
second_title: Aspose.Slides Java API hivatkozás
description: Digitális aláírás az aláírt fájlban.
type: docs
url: /hu/com.aspose.slides/digitalsignature/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Digitális aláírás az aláírt fájlban.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Inicializálja a Presentation példányt
>  Presentation pres = new Presentation();
>  try {
>     // Létrehozza a DigitalSignature objektumot PFX fájl és PFX jelszó használatával
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Az új digitális aláírás megjegyzése
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Digitális aláírás hozzáadása a prezentációhoz
>      pres.getDigitalSignatures().add(signature);
>      // Prezentáció mentése
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Inicializálja a Presentation példányt
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Ellenőrzi, hogy az összes digitális aláírás érvényes-e
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

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Létrehoz egy új DigitalSignature objektumot a megadott tanúsítvánnyal. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Létrehoz egy új DigitalSignature objektumot a megadott tanúsítványfájl úttal és jelszóval. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCertificate()](#getCertificate--) | Certificate objektum, amelyet a dokumentum aláírásához használtak. |
| [isValid()](#isValid--) | Ha ez a digitális aláírás érvényes, és a dokumentumot nem módosították, ez az érték igaz lesz. |
| [getSignTime()](#getSignTime--) | A dokumentum aláírásának időpontja. |
| [getComments()](#getComments--) | Az aláírás célja. |
| [setComments(String value)](#setComments-java.lang.String-) | Az aláírás célja. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

Létrehoz egy új DigitalSignature objektumot a megadott tanúsítvánnyal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| certData | byte[] | a tanúsítványt tartalmazó bájt tömb |
| password | java.lang.String | A tanúsítvány eléréséhez szükséges jelszó. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

Létrehoz egy új DigitalSignature objektumot a megadott tanúsítványfájl úttal és jelszóval.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filePath | java.lang.String | A tanúsítványt tartalmazó fájl elérési útja. |
| password | java.lang.String | A tanúsítvány eléréséhez szükséges jelszó. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

Certificate objektum, amelyet a dokumentum aláírásához használtak. Csak olvasható byte[].

**Visszatérési érték:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```

Ha ez a digitális aláírás érvényes, és a dokumentumot nem módosították, ez az érték igaz lesz. Csak olvasható boolean.

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

**Visszatérési érték:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

A dokumentum aláírásának időpontja. Csak olvasható java.util.Date.

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

**Visszatérési érték:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```

Az aláírás célja. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Az aláírás célja. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |