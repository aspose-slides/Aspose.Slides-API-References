---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digital signature in signed file.
type: docs
url: /sv/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Digital signatur i en signerad fil.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCertificate()](#getCertificate--) | Certifikatobjekt som användes för att signera dokumentet. |
| [isValid()](#isValid--) | Om den här digitala signaturen är giltig och dokumentet inte har manipulerats, blir detta värde sant. |
| [getSignTime()](#getSignTime--) | Tidpunkten då dokumentet signerades. |
| [getComments()](#getComments--) | Syftet med signaturen. |
| [setComments(String value)](#setComments-java.lang.String-) | Syftet med signaturen. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```


Certifikatobjekt som användes för att signera dokumentet. Skrivskyddad byte[].

**Returnerar:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```


Om den här digitala signaturen är giltig och dokumentet inte har manipulerats, blir detta värde sant. Skrivskyddad boolean.

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
public abstract Date getSignTime()
```


Tidpunkten då dokumentet signerades. Skrivskyddad java.util.Date.

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

**Returnerar:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```


Syftet med signaturen. Läs/skriv String.

**Returnerar:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


Syftet med signaturen. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |