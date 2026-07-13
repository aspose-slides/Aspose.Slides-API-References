---
title: DigitalSignature
second_title: Aspose.Slides dla Androida - referencja API Java
description: Podpis cyfrowy w podpisanym pliku.
type: docs
url: /pl/com.aspose.slides/digitalsignature/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Podpis cyfrowy w podpisanym pliku.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Zainicjalizuj instancję Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Utwórz obiekt DigitalSignature z plikiem PFX i hasłem PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Dodaj komentarz do nowego podpisu cyfrowego
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Dodaj podpis cyfrowy do prezentacji
>      pres.getDigitalSignatures().add(signature);
>      // Zapisz prezentację
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Zainicjalizuj instancję Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Sprawdź, czy wszystkie podpisy cyfrowe są ważne
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

| Konstruktor | Opis |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Tworzy nowy obiekt DigitalSignature z podanym certyfikatem. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Tworzy nowy obiekt DigitalSignature z podaną ścieżką do pliku certyfikatu i hasłem. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getCertificate()](#getCertificate--) | Obiekt certyfikatu użyty do podpisania dokumentu. |
| [isValid()](#isValid--) | Jeśli ten podpis cyfrowy jest ważny i dokument nie został zmodyfikowany, wartość będzie prawda. |
| [getSignTime()](#getSignTime--) | Czas, w którym dokument został podpisany. |
| [getComments()](#getComments--) | Cel podpisu. |
| [setComments(String value)](#setComments-java.lang.String-) | Cel podpisu. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


Tworzy nowy obiekt DigitalSignature z podanym certyfikatem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| certData | byte[] | tablica bajtów zawierająca certyfikat |
| password | java.lang.String | Hasło wymagane do uzyskania dostępu do certyfikatu. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


Tworzy nowy obiekt DigitalSignature z podaną ścieżką do pliku certyfikatu i hasłem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| filePath | java.lang.String | Ścieżka do pliku z certyfikatem. |
| password | java.lang.String | Hasło wymagane do uzyskania dostępu do certyfikatu. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


Obiekt certyfikatu użyty do podpisania dokumentu. Tylko do odczytu byte[].

**Zwraca:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


Jeśli ten podpis cyfrowy jest ważny i dokument nie został zmodyfikowany, wartość będzie prawda. Tylko do odczytu boolean.

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

**Zwraca:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Czas, w którym dokument został podpisany. Tylko do odczytu java.util.Date.

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

**Zwraca:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


Cel podpisu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Cel podpisu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |