---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Información sobre el archivo de presentación
type: docs
url: /es/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Información sobre el archivo de presentación
## Métodos

| Método | Descripción |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Obtiene True si la presentación vinculada está cifrada, de lo contrario False. |
| [isPasswordProtected()](#isPasswordProtected--) | Obtiene un valor que indica si la presentación vinculada está protegida por una contraseña para abrir. |
| [isWriteProtected()](#isWriteProtected--) | Obtiene un valor que indica si la presentación vinculada está protegida contra escritura. |
| [getLoadFormat()](#getLoadFormat--) | Obtiene el formato de la presentación vinculada. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Comprueba si una contraseña es correcta para una presentación protegida con contraseña de apertura. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Comprueba si una contraseña para modificar es correcta para una presentación protegida contra escritura. |
| [readDocumentProperties()](#readDocumentProperties--) | Obtiene las propiedades del documento de la presentación vinculada. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Actualiza las propiedades de la presentación vinculada. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Escribe la presentación vinculada en un stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Escribe la presentación vinculada en un archivo. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Obtiene True si la presentación vinculada está cifrada, de lo contrario False. Solo lectura boolean.

**Devuelve:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Obtiene un valor que indica si la presentación vinculada está protegida por una contraseña para abrir.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**Devuelve:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Obtiene un valor que indica si la presentación vinculada está protegida contra escritura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Si la presentación está protegida por una contraseña para abrir, el valor de la propiedad es igual a NotDefined. Consulte la enumeración [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Obtiene el formato de la presentación vinculada. Solo lectura [LoadFormat](../../com.aspose.slides/loadformat).

**Devuelve:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Comprueba si una contraseña es correcta para una presentación protegida con contraseña de apertura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | java.lang.String | La contraseña a verificar. |

--------------------

Cuando la contraseña es null o vacía, este método devuelve false.

**Devuelve:**
boolean - True si la presentación está protegida con contraseña de apertura y la contraseña es correcta y false en caso contrario.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Comprueba si una contraseña para modificar es correcta para una presentación protegida contra escritura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | java.lang.String | La contraseña a verificar. |

--------------------

1. Debe comprobar la propiedad (\#isWriteProtected.isWriteProtected) antes de llamar a este método. 2. Cuando la contraseña es null o vacía, este método devuelve false.

**Devuelve:**
boolean - True si la presentación está protegida contra escritura y la contraseña es correcta. False en caso contrario.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Obtiene las propiedades del documento de la presentación vinculada.

**Devuelve:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Propiedades del documento [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Actualiza las propiedades de la presentación vinculada.

--------------------

> ```
> Este ejemplo muestra cómo llamar al #updateDocumentProperties(IDDocumentProperties).updateDocumentProperties(IDDocumentProperties) método para
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Propiedades del documento [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Escribe la presentación vinculada en un stream.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | El stream debe ser buscable y escribible. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Escribe la presentación vinculada en un archivo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | java.lang.String | Archivo de presentación. |