---
title: DigitalSignature
second_title: Referencia de API Java de Aspose.Slides para Android
description: Firma digital en archivo firmado.
type: docs
url: /es/com.aspose.slides/digitalsignature/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Firma digital en archivo firmado.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Inicializar la instancia de Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Crear objeto DigitalSignature con archivo PFX y contraseña PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Comentar nueva firma digital
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Agregar firma digital a la presentación
>      pres.getDigitalSignatures().add(signature);
>      // Guardar presentación
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Inicializar la instancia de Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Comprobar si todas las firmas digitales son válidas
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

## Constructores

| Constructor | Descripción |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Crea un nuevo objeto DigitalSignature con el certificado especificado. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Crea un nuevo objeto DigitalSignature con la ruta del archivo de certificado y la contraseña especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objeto de certificado que se utilizó para firmar el documento. |
| [isValid()](#isValid--) | Si esta firma digital es válida y el documento no ha sido manipulado, este valor será verdadero. |
| [getSignTime()](#getSignTime--) | La hora en que se firmó el documento. |
| [getComments()](#getComments--) | El propósito de la firma. |
| [setComments(String value)](#setComments-java.lang.String-) | El propósito de la firma. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


Crea un nuevo objeto DigitalSignature con el certificado especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| certData | byte[] | una matriz de bytes que contiene el certificado |
| password | java.lang.String | Contraseña requerida para acceder al certificado. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


Crea un nuevo objeto DigitalSignature con la ruta del archivo de certificado y la contraseña especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | Ruta al archivo con el certificado. |
| password | java.lang.String | Contraseña requerida para acceder al certificado. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


Objeto de certificado que se utilizó para firmar el documento. Solo lectura byte[].

**Devuelve:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


Si esta firma digital es válida y el documento no ha sido manipulado, este valor será verdadero. Solo lectura boolean.

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

**Devuelve:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


La hora en que se firmó el documento. Solo lectura java.util.Date.

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

**Devuelve:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


El propósito de la firma. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


El propósito de la firma. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |