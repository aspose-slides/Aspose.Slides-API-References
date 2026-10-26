---
title: DigitalSignature
second_title: Aspose.Slides pro Android - referenční příručka Java API
description: Digitální podpis v podepsaném souboru.
type: docs
url: /cs/com.aspose.slides/digitalsignature/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Digitální podpis v podepsaném souboru.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Inicializovat instanci Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Vytvořit objekt DigitalSignature s PFX souborem a PFX heslem
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Komentovat nový digitální podpis
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Přidat digitální podpis do prezentace
>      pres.getDigitalSignatures().add(signature);
>      // Uložit prezentaci
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Inicializovat instanci Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Zkontrolovat, zda jsou všechny digitální podpisy platné
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

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Vytvoří nový objekt DigitalSignature se zadaným certifikátem. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Vytvoří nový objekt DigitalSignature se zadanou cestou k souboru certifikátu a heslem. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objekt certifikátu, který byl použit k podepsání dokumentu. |
| [isValid()](#isValid--) | Pokud je tento digitální podpis platný a dokument nebyl pozměněn, bude tato hodnota true. |
| [getSignTime()](#getSignTime--) | Čas, kdy byl dokument podepsán. |
| [getComments()](#getComments--) | Účel podpisu. |
| [setComments(String value)](#setComments-java.lang.String-) | Účel podpisu. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

Vytvoří nový objekt DigitalSignature se zadaným certifikátem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| certData | byte[] | pole bajtů obsahující certifikát |
| password | java.lang.String | Heslo potřebné pro přístup k certifikátu. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

Vytvoří nový objekt DigitalSignature se zadanou cestou k souboru certifikátu a heslem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| filePath | java.lang.String | Cesta k souboru s certifikátem. |
| password | java.lang.String | Heslo potřebné pro přístup k certifikátu. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

Objekt certifikátu, který byl použit k podepsání dokumentu. Pouze pro čtení byte[].

**Vrací:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```

Pokud je tento digitální podpis platný a dokument nebyl pozměněn, bude tato hodnota true. Pouze pro čtení boolean.

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


**Vrací:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

Čas, kdy byl dokument podepsán. Pouze pro čtení java.util.Date.

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

**Vrací:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```

Účel podpisu. Čtení/zápis String.

**Vrací:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Účel podpisu. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |