---
title: ProtectionManager
second_title: Referencia de API Java de Aspose.Slides para Android
description: Gestión de protección de contraseña de presentaciones.
type: docs
url: /es/com.aspose.slides/protectionmanager/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Gestión de protección de contraseña de presentaciones.
## Métodos

| Método | Descripción |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Esta propiedad tiene sentido si la presentación está protegida con contraseña. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Esta propiedad tiene sentido si la presentación está protegida con contraseña. |
| [isEncrypted()](#isEncrypted--) | Obtiene un valor que indica si esta instancia está encriptada. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña y las propiedades del documento de este archivo son públicas. |
| [isWriteProtected()](#isWriteProtected--) | Obtiene un valor que indica si esta presentación está protegida contra escritura. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Encripta la presentación con la contraseña especificada. |
| [removeEncryption()](#removeEncryption--) | Elimina la encriptación. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Establece protección contra escritura para esta presentación con la contraseña especificada. |
| [removeWriteProtection()](#removeWriteProtection--) | Elimina la protección contra escritura para esta presentación. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Determina si una presentación está protegida con contraseña para modificarla. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Obtiene la contraseña utilizada para la encriptación de la presentación. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Obtiene o establece la recomendación de solo lectura. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Obtiene o establece la recomendación de solo lectura. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Esta propiedad tiene sentido si la presentación está protegida con contraseña. Si es true, las propiedades del documento están encriptadas en el archivo de presentación. Si es false, las propiedades del documento son públicas mientras la presentación está encriptada. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Esta propiedad tiene sentido si la presentación está protegida con contraseña. Si es true, las propiedades del documento están encriptadas en el archivo de presentación. Si es false, las propiedades del documento son públicas mientras la presentación está encriptada. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Obtiene un valor que indica si esta instancia está encriptada. Booleano de solo lectura.

Valor: true si la presentación se cargó desde un archivo encriptado o se llamó al método \#encrypt(String).encrypt(String); de lo contrario, false.

**Devuelve:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña y las propiedades del documento de este archivo son públicas. El valor true significa que solo se cargan las propiedades del documento de un archivo de presentación encriptado sin usar contraseña. El valor false indica que se carga toda la presentación encriptada con la contraseña correcta, no solo las propiedades del documento. Si la presentación no está encriptada, el valor de la propiedad es siempre false. Si las propiedades del documento de un archivo encriptado no son públicas, el valor de la propiedad es siempre false. Si Presentation.EncryptDocumentProperties es true, entonces el valor de IsOnlyDocumentPropertiesLoaded es siempre false. Booleano de solo lectura.

**Devuelve:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Obtiene un valor que indica si esta presentación está protegida contra escritura. Booleano de solo lectura.

**Devuelve:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Encripta la presentación con la contraseña especificada.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encryptionPassword | java.lang.String | La contraseña. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Elimina la encriptación.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Establece protección contra escritura para esta presentación con la contraseña especificada.

--------------------

> ```
> The following sample code shows you how to set a write protection to a presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | java.lang.String | La contraseña. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Elimina la protección contra escritura para esta presentación.

--------------------

> ```
> Este código de ejemplo muestra cómo eliminar la protección contra escritura de una presentación PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Determina si una presentación está protegida con contraseña para modificarla.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | java.lang.String | La contraseña para la comprobación. |

1. Debe comprobar la propiedad (\#isWriteProtected.isWriteProtected) antes de llamar a este método. 2. Cuando la contraseña es null o está vacía, este método devuelve false.

**Devuelve:**
boolean - true si la contraseña es válida; de lo contrario, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Obtiene la contraseña utilizada para la encriptación de la presentación. Cadena de solo lectura.

**Devuelve:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Obtiene o establece la recomendación de solo lectura. Booleano de lectura/escritura.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Obtiene o establece la recomendación de solo lectura. Booleano de lectura/escritura.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |