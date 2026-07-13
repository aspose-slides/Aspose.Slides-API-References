---
title: DigitalSignature
second_title: Riferimento API Java di Aspose.Slides per Android
description: Firma digitale nel file firmato.
type: docs
url: /it/com.aspose.slides/digitalsignature/
---
**Ereditarietà:**
java.lang.Object

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Firma digitale nel file firmato.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Inizializza istanza Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Crea oggetto DigitalSignature con file PFX e password PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Commenta nuova firma digitale
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Aggiungi firma digitale alla presentazione
>      pres.getDigitalSignatures().add(signature);
>      // Salva presentazione
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Inizializza istanza Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Verifica se tutte le firme digitali sono valide
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

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Crea un nuovo oggetto DigitalSignature con il certificato specificato. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Crea un nuovo oggetto DigitalSignature con il percorso del file del certificato e la password specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCertificate()](#getCertificate--) | Oggetto certificato utilizzato per firmare il documento. |
| [isValid()](#isValid--) | Se questa firma digitale è valida e il documento non è stato manomesso, questo valore sarà true. |
| [getSignTime()](#getSignTime--) | Il momento in cui il documento è stato firmato. |
| [getComments()](#getComments--) | Lo scopo della firma. |
| [setComments(String value)](#setComments-java.lang.String-) | Lo scopo della firma. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


Crea un nuovo oggetto DigitalSignature con il certificato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certData | byte[] | un array di byte contenente il certificato |
| password | java.lang.String | Password necessaria per accedere al certificato. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


Crea un nuovo oggetto DigitalSignature con il percorso del file del certificato e la password specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Percorso al file con il certificato. |
| password | java.lang.String | Password necessaria per accedere al certificato. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


Oggetto certificato utilizzato per firmare il documento. Solo lettura byte[].

**Restituisce:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
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
public final Date getSignTime()
```


Il momento in cui il documento è stato firmato. Solo lettura java.util.Date.

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

**Restituisce:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


Lo scopo della firma. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Lo scopo della firma. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |