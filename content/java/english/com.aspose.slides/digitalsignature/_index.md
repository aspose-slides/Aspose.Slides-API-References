---
title: DigitalSignature
second_title: Aspose.Slides for Java API Reference
description: Digital signature in signed file.
type: docs
url: /com.aspose.slides/digitalsignature/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Digital signature in signed file.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Initialize Presentation instance
>  Presentation pres = new Presentation();
>  try {
>     // Create DigitalSignature object with PFX file and PFX password
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Comment new digital signature
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Add digital signature to presentation
>      pres.getDigitalSignatures().add(signature);
>      // Save presentation
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Initialize Presentation instance
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Check if all digital signatures are valid
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
## Constructors

| Constructor | Description |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Creates a new DigitalSignature object with the specified certificate. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Creates a new DigitalSignature object with the specified certificate file path and password. |
## Methods

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | Certificate object that was used to sign the document. |
| [isValid()](#isValid--) | If this digital signature is valid and the document has not been tampered with, this value will be true. |
| [getSignTime()](#getSignTime--) | The time when the document was signed. |
| [getComments()](#getComments--) | The purpose of signature. |
| [setComments(String value)](#setComments-java.lang.String-) | The purpose of signature. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


Creates a new DigitalSignature object with the specified certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certData | byte[] | a byte array containing the certificate |
| password | java.lang.String | Password required to access certificate. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


Creates a new DigitalSignature object with the specified certificate file path and password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Path to the file with certificate. |
| password | java.lang.String | Password required to access certificate. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


Certificate object that was used to sign the document. Read-only byte[].

**Returns:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only boolean.

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

**Returns:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


The time when the document was signed. Read-only java.util.Date.

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

**Returns:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


The purpose of signature. Read/write String.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


The purpose of signature. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

