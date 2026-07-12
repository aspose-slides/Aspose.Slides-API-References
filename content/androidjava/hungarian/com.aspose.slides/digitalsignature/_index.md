---
title: DigitalSignature
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Digitális aláírás a aláírt fájlban.
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

Digitális aláírás a aláírt fájlban.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Inicializálja a Presentation példányt
>  Presentation pres = new Presentation();
>  try {
>     // DigitalSignature objektum létrehozása PFX fájllal és PFX jelszóval
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Új digitális aláírás megjegyzése
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
>          // Ellenőrizze, hogy minden digitális aláírás érvényes-e
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
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Új DigitalSignature objektumot hoz létre a megadott tanúsítvánnyal. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Új DigitalSignature objektumot hoz létre a megadott tanúsítványfájl elérési úttal és jelszóval. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCertificate()](#getCertificate--) | Tanúsítvány objektum, amelyet a dokumentum aláírásához használtak. |
| [isValid()](#isValid--) | Ha ez a digitális aláírás érvényes és a dokumentumot nem módosították, akkor ez az érték true lesz. |
| [getSignTime()](#getSignTime--) | A dokumentum aláírásának időpontja. |
| [getComments()](#getComments--) | Az aláírás célja. |
| [setComments(String value)](#setComments-java.lang.String-) | Az aláírás célja. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


Új DigitalSignature objektumot hoz létre a megadott tanúsítvánnyal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| certData | byte[] | a tanúsítványt tartalmazó bájt tömb |
| password | java.lang.String | A tanúsítvány eléréséhez szükséges jelszó. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


Új DigitalSignature objektumot hoz létre a megadott tanúsítványfájl elérési úttal és jelszóval.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filePath | java.lang.String | Az tanúsítványt tartalmazó fájl elérési útja. |
| password | java.lang.String | A tanúsítvány eléréséhez szükséges jelszó. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


Tanúsítvány objektum, amelyet a dokumentum aláírásához használtak. Csak olvasható byte[].

**Visszatérési érték:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


Ha ez a digitális aláírás érvényes és a dokumentumot nem módosították, akkor ez az érték true lesz. Csak olvasható boolean.

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


Az aláírás célja. Olvasható/írható String.

**Visszatérési érték:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Az aláírás célja. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |