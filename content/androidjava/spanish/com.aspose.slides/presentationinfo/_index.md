---
title: PresentationInfo
second_title: Aspose.Slides para Android a través de la referencia API de Java
description: Información sobre el archivo de presentación
type: docs
url: /es/com.aspose.slides/presentationinfo/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Información sobre el archivo de presentación
## Métodos

| Método | Descripción |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Obtiene True si la presentación vinculada está encriptada, de lo contrario False. |
| [isPasswordProtected()](#isPasswordProtected--) | Obtiene un valor que indica si la presentación vinculada está protegida por una contraseña para abrir. |
| [isWriteProtected()](#isWriteProtected--) | Obtiene un valor que indica si la presentación vinculada está protegida contra escritura. |
| [getLoadFormat()](#getLoadFormat--) | Obtiene el formato de la presentación vinculada. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Comprueba si una contraseña es correcta para una presentación protegida con contraseña de apertura. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Comprueba si una contraseña de modificación es correcta para una presentación protegida contra escritura. |
| [readDocumentProperties()](#readDocumentProperties--) | Obtiene las propiedades del documento de la presentación vinculada. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Actualiza las propiedades de la presentación vinculada. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Escribe la presentación vinculada al flujo. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Escribe la presentación vinculada al archivo. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Obtiene True si la presentación vinculada está encriptada, de lo contrario False. Solo lectura booleano.

**Devuelve:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Obtiene un valor que indica si la presentación vinculada está protegida por una contraseña para abrir.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Devuelve:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```


Obtiene un valor que indica si la presentación vinculada está protegida contra escritura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

Si la presentación está protegida por una contraseña para abrir, el valor de la propiedad es igual a NotDefined.

**Devuelve:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


Obtiene el formato de la presentación vinculada. Solo lectura [LoadFormat](../../com.aspose.slides/loadformat).

**Devuelve:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```


Comprueba si una contraseña es correcta para una presentación protegida con contraseña de apertura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | java.lang.String | La contraseña a comprobar.

--------------------

Cuando la contraseña es nula o está vacía, este método devuelve false. |

**Devuelve:**
boolean - True si la presentación está protegida con contraseña de apertura y la contraseña es correcta y false de lo contrario.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


Comprueba si una contraseña de modificación es correcta para una presentación protegida contra escritura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | java.lang.String | La contraseña a comprobar.

--------------------

1. Debe comprobar la propiedad (\#isWriteProtected.isWriteProtected) antes de llamar a este método. 2. Cuando la contraseña es nula o está vacía, este método devuelve false. |

**Devuelve:**
boolean - True si la presentación está protegida contra escritura y la contraseña es correcta. False de lo contrario.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```


Obtiene las propiedades del documento de la presentación vinculada.

**Devuelve:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```


Actualiza las propiedades de la presentación vinculada.

--------------------

> ```
> Este ejemplo muestra cómo llamar al método #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDDocumentProperties) para
>  actualizar las propiedades del documento devueltas por la llamada al método #readDocumentProperties.readDocumentProperties.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```


Escribe la presentación vinculada al flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | El flujo debe ser posicionable y escribible. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```


Escribe la presentación vinculada al archivo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | java.lang.String | Archivo de presentación.