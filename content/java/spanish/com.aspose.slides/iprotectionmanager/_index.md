---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: Gestión de protección con contraseña de la presentación.
type: docs
url: /es/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Gestión de protección con contraseña de la presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Esta propiedad tiene sentido si la presentación está protegida con contraseña. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Esta propiedad tiene sentido si la presentación está protegida con contraseña. |
| [isEncrypted()](#isEncrypted--) | Obtiene un valor que indica si esta instancia está encriptada. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Esta propiedad tiene sentido si el archivo de la presentación está protegido con contraseña y las propiedades del documento de este archivo son públicas. |
| [isWriteProtected()](#isWriteProtected--) | Obtiene un valor que indica si esta presentación está protegida contra escritura. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Devuelve la contraseña de encriptación. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Obtiene o establece la recomendación de solo lectura. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Obtiene o establece la recomendación de solo lectura. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Encripta la presentación con la contraseña especificada. |
| [removeEncryption()](#removeEncryption--) | Elimina la encriptación. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Establece protección contra escritura para esta presentación con la contraseña especificada. |
| [removeWriteProtection()](#removeWriteProtection--) | Elimina la protección contra escritura para esta presentación. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Determina si una presentación está protegida con contraseña para modificar. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```


Esta propiedad tiene sentido si la presentación está protegida con contraseña. Si es true, las propiedades del documento están encriptadas en el archivo de la presentación. Si es false, las propiedades del documento son públicas mientras la presentación está encriptada. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```


Esta propiedad tiene sentido si la presentación está protegida con contraseña. Si es true, las propiedades del documento están encriptadas en el archivo de la presentación. Si es false, las propiedades del documento son públicas mientras la presentación está encriptada. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Obtiene un valor que indica si esta instancia está encriptada. Booleano de solo lectura.

Valor: true si la presentación se cargó desde un archivo encriptado o se llamó al método \#encrypt(String).encrypt(String); de lo contrario, false.

**Devuelve:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```


Esta propiedad tiene sentido si el archivo de la presentación está protegido con contraseña y las propiedades del documento de este archivo son públicas. El valor true significa que solo se cargan las propiedades del documento de un archivo de presentación encriptado sin usar contraseña. El valor false significa que se carga la presentación completa encriptada usando la contraseña correcta, no solo las propiedades del documento. Si la presentación no está encriptada, el valor de la propiedad siempre es false. Si las propiedades del documento de un archivo encriptado no son públicas, el valor de la propiedad siempre es false. Si PresentationEx.EncryptDocumentProperties es true, entonces el valor de la propiedad IsOnlyDocumentPropertiesLoaded siempre es false. Booleano de solo lectura.

**Devuelve:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```


Obtiene un valor que indica si esta presentación está protegida contra escritura. Booleano de solo lectura.

**Devuelve:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```


Devuelve la contraseña de encriptación. Cadena de solo lectura.

**Devuelve:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```


Obtiene o establece la recomendación de solo lectura. Booleano de lectura/escritura.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Devuelve:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```


Obtiene o establece la recomendación de solo lectura. Booleano de lectura/escritura.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```


Encripta la presentación con la contraseña especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encryptionPassword | java.lang.String | La contraseña. |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```


Elimina la encriptación.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```


Establece protección contra escritura para esta presentación con la contraseña especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | java.lang.String | La contraseña. |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```


Elimina la protección contra escritura para esta presentación.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


Determina si una presentación está protegida con contraseña para modificar.

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
| password | java.lang.String | La contraseña para la verificación.

--------------------

1. Debe comprobar la propiedad (\#isWriteProtected.isWriteProtected) antes de llamar a este método. 2. Cuando la contraseña es nula o vacía, este método devuelve false. |

**Devuelve:**
boolean - true si la contraseña es válida; de lo contrario, false.