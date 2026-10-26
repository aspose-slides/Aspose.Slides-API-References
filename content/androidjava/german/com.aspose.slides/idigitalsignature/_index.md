---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digitale Signatur in einer signierten Datei.
type: docs
url: /de/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Digitale Signatur in einer signierten Datei.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCertificate()](#getCertificate--) | Zertifikatsobjekt, das zum Signieren des Dokuments verwendet wurde. |
| [isValid()](#isValid--) | Wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde, ist dieser Wert true. |
| [getSignTime()](#getSignTime--) | Der Zeitpunkt, zu dem das Dokument signiert wurde. |
| [getComments()](#getComments--) | Der Zweck der Signatur. |
| [setComments(String value)](#setComments-java.lang.String-) | Der Zweck der Signatur. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```


Zertifikatsobjekt, das zum Signieren des Dokuments verwendet wurde. Nur lesbar byte[].

**Rückgabe:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```


Wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde, ist dieser Wert true. Nur lesbar boolean.

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

**Rückgabe:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```


Der Zeitpunkt, zu dem das Dokument signiert wurde. Nur lesbar java.util.Date.

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


**Rückgabe:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```


Der Zweck der Signatur. Lese-/Schreibzugriff String.

**Rückgabe:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


Der Zweck der Signatur. Lese-/Schreibzugriff String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |