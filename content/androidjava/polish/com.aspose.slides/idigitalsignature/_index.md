---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Podpis cyfrowy w podpisanym pliku.
type: docs
url: /pl/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Podpis cyfrowy w podpisanym pliku.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCertificate()](#getCertificate--) | Obiekt certyfikatu użyty do podpisania dokumentu. |
| [isValid()](#isValid--) | Jeśli ten podpis cyfrowy jest prawidłowy i dokument nie został zmodyfikowany, ta wartość będzie prawdziwa. |
| [getSignTime()](#getSignTime--) | Czas, w którym dokument został podpisany. |
| [getComments()](#getComments--) | Cel podpisu. |
| [setComments(String value)](#setComments-java.lang.String-) | Cel podpisu. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```


Obiekt certyfikatu użyty do podpisania dokumentu. Tylko do odczytu byte[].

**Zwraca:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```


Jeśli ten podpis cyfrowy jest prawidłowy i dokument nie został zmodyfikowany, ta wartość będzie prawdziwa. Tylko do odczytu boolean.

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
public abstract Date getSignTime()
```


Czas, w którym dokument został podpisany. Tylko do odczytu java.util.Date.

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


**Zwraca:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```


Cel podpisu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


Cel podpisu. Odczyt/zapis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |