---
title: IOleObjectFrame
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un objeto OLE en una diapositiva.
type: docs
url: /es/com.aspose.slides/ioleobjectframe/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Representa un objeto OLE en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Devuelve el objeto de propiedades de relleno de imagen OleObject. |
| [getObjectName()](#getObjectName--) | Devuelve o establece el nombre de un objeto. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Devuelve o establece el nombre de un objeto. |
| [getEmbeddedData()](#getEmbeddedData--) | Obtiene información sobre los datos incrustados OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Establece información sobre los datos incrustados OLE. |
| [getObjectProgId()](#getObjectProgId--) | Devuelve el ProgID de un objeto. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Devuelve el ProgID de un objeto. |
| [getLinkFileName()](#getLinkFileName--) | Devuelve la ruta completa a un archivo vinculado. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve la ruta completa a un archivo vinculado. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Devuelve la ruta completa a un archivo vinculado. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Devuelve la ruta relativa a un archivo vinculado si está presente, de lo contrario devuelve una cadena vacía. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Devuelve el nombre del archivo del objeto OLE incrustado |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Devuelve la ruta del objeto OLE incrustado |
| [isObjectIcon()](#isObjectIcon--) | Determina si un objeto es visible como ícono. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Determina si un objeto es visible como ícono. |
| [isObjectLink()](#isObjectLink--) | Determina si un objeto está vinculado a un archivo externo. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Determina si el objeto incrustado vinculado se actualiza automáticamente cuando la presentación se abre o se imprime. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Determina si el objeto incrustado vinculado se actualiza automáticamente cuando la presentación se abre o se imprime. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Devuelve o establece el título del ícono OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Devuelve o establece el título del ícono OleObject. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Devuelve el objeto de propiedades de relleno de imagen OleObject. Solo lectura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Devuelve:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```


Devuelve o establece el nombre de un objeto. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


Devuelve o establece el nombre de un objeto. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


Obtiene información sobre los datos incrustados OLE. Solo lectura [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Devuelve:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


Establece información sobre los datos incrustados OLE.

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Datos incrustados [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

Este método cambia las propiedades del objeto para reflejar los nuevos datos y establece la bandera IsObjectLink a false, indicando que el objeto OLE está incrustado. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```


Devuelve el ProgID de un objeto. Solo lectura String.

**Devuelve:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```


Devuelve el ProgID de un objeto. Solo lectura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


Devuelve la ruta completa a un archivo vinculado. Se usará el nombre corto del archivo. Solo lectura String.

**Devuelve:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Devuelve la ruta completa a un archivo vinculado. Se usará el nombre largo del archivo. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Devuelve la ruta completa a un archivo vinculado. Se usará el nombre largo del archivo. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```


Devuelve la ruta relativa a un archivo vinculado si está presente, de lo contrario devuelve una cadena vacía. Solo lectura String.

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


En las presentaciones Ppt, algunos enlaces de objetos Ole pueden tener una representación relativa.

**Devuelve:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```


Devuelve el nombre del archivo del objeto OLE incrustado

**Devuelve:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```


Devuelve la ruta del objeto OLE incrustado

**Devuelve:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```


Determina si un objeto es visible como ícono. Lectura/escritura boolean.

**Devuelve:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```


Determina si un objeto es visible como ícono. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```


Determina si un objeto está vinculado a un archivo externo. Solo lectura boolean.

**Devuelve:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


Determina si el objeto incrustado vinculado se actualiza automáticamente cuando la presentación se abre o se imprime. Lectura/escritura boolean.

**Devuelve:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


Determina si el objeto incrustado vinculado se actualiza automáticamente cuando la presentación se abre o se imprime. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


Devuelve o establece el título del ícono OleObject. Lectura/escritura String.

Cuando IsObjectIcon == false este valor se ignora. La cadena puede truncarse según el tamaño del icono OLE.

**Devuelve:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


Devuelve o establece el título del ícono OleObject. Lectura/escritura String.

Cuando IsObjectIcon == false este valor se ignora. La cadena puede truncarse según el tamaño del icono OLE.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |