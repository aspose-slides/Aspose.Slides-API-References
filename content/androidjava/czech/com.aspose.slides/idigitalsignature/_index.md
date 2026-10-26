---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digitální podpis v podepsaném souboru.
type: docs
url: /cs/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Digitální podpis v podepsaném souboru.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objekt certifikátu, který byl použit k podepsání dokumentu. |
| [isValid()](#isValid--) | Pokud je tento digitální podpis platný a dokument nebyl poškozen, bude tato hodnota true. |
| [getSignTime()](#getSignTime--) | Čas, kdy byl dokument podepsán. |
| [getComments()](#getComments--) | Účel podpisu. |
| [setComments(String value)](#setComments-java.lang.String-) | Účel podpisu. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Objekt certifikátu, který byl použit k podepsání dokumentu. Pouze pro čtení byte[].

**Vrací:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

Pokud je tento digitální podpis platný a dokument nebyl poškozen, bude tato hodnota true. Pouze pro čtení boolean.

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
public abstract Date getSignTime()
```

Čas, kdy byl dokument podepsán. Pouze pro čtení java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.IsValid ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

Účel podpisu. Čtení/zápis String.

**Vrací:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Účel podpisu. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |