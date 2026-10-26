---
title: IDigitalSignature
second_title: Aspose.Slides para Java Referência da API
description: Assinatura digital em arquivo assinado.
type: docs
url: /pt/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Assinatura digital em arquivo assinado.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objeto Certificate que foi usado para assinar o documento. |
| [isValid()](#isValid--) | Se esta assinatura digital for válida e o documento não tiver sido adulterado, este valor será verdadeiro. |
| [getSignTime()](#getSignTime--) | O horário em que o documento foi assinado. |
| [getComments()](#getComments--) | O propósito da assinatura. |
| [setComments(String value)](#setComments-java.lang.String-) | O propósito da assinatura. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Objeto Certificate que foi usado para assinar o documento. Somente leitura byte[].

**Retorna:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

Se esta assinatura digital for válida e o documento não tiver sido adulterado, este valor será verdadeiro. Somente leitura boolean.

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


**Retorna:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```

O horário em que o documento foi assinado. Somente leitura java.util.Date.

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


**Retorna:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

O propósito da assinatura. Leitura/gravação String.

**Retorna:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

O propósito da assinatura. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |