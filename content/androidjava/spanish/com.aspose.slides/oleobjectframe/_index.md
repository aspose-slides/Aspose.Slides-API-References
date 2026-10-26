---
title: OleObjectFrame
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa un objeto OLE en una diapositiva.
type: docs
url: /es/com.aspose.slides/oleobjectframe/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Representa un objeto OLE en una diapositiva.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Carga el PPTX a un objeto de presentación
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Accede a la primera diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Convierte la forma a OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Lee el objeto OLE y lo escribe en disco
>      if (oleObjectFrame != null) {
>          // Obtiene los datos del archivo incrustado
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Obtiene la extensión del archivo incrustado
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Crea una ruta para guardar el archivo extraído
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Guarda los datos extraídos
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descripción |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Devuelve el objeto de propiedades de relleno de imagen OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Devuelve o establece el título del icono OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Devuelve o establece el título del icono OleObject. |
| [getObjectName()](#getObjectName--) | Devuelve o establece el nombre de un objeto. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Devuelve o establece el nombre de un objeto. |
| [getObjectProgId()](#getObjectProgId--) | Devuelve el ProgID de un objeto. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Devuelve el ProgID de un objeto. |
| [getLinkFileName()](#getLinkFileName--) | Devuelve la ruta completa a un archivo enlazado. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve la ruta completa a un archivo enlazado. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Devuelve la ruta completa a un archivo enlazado. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Devuelve la ruta relativa a un archivo enlazado si está presente; de lo contrario, devuelve una cadena vacía. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Devuelve el nombre de archivo del objeto OLE incrustado |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Devuelve la ruta del objeto OLE incrustado |
| [getEmbeddedData()](#getEmbeddedData--) | Obtiene o establece información sobre datos OLE incrustados. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Establece información sobre datos OLE incrustados. |
| [isObjectIcon()](#isObjectIcon--) | Determina si un objeto es visible como icono. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Determina si un objeto es visible como icono. |
| [isObjectLink()](#isObjectLink--) | Determina si un objeto está enlazado a un archivo externo. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Determina si el objeto incrustado enlazado se actualiza automáticamente cuando la presentación se abre o se imprime. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Determina si el objeto incrustado enlazado se actualiza automáticamente cuando la presentación se abre o se imprime. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Devuelve el objeto de propiedades de relleno de imagen OleObject. Solo lectura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Devuelve:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Devuelve o establece el título del icono OleObject. Lectura/escritura String.

--------------------

Cuando IsObjectIcon == false este valor se ignora. La cadena puede truncarse según el tamaño del icono Ole.

**Devuelve:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Devuelve o establece el título del icono OleObject. Lectura/escritura String.

--------------------

Cuando IsObjectIcon == false este valor se ignora. La cadena puede truncarse según el tamaño del icono Ole.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Devuelve o establece el nombre de un objeto. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Devuelve o establece el nombre de un objeto. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Devuelve el ProgID de un objeto. Solo lectura String.

**Devuelve:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Devuelve el ProgID de un objeto. Solo lectura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Devuelve la ruta completa a un archivo enlazado. Se usará el nombre corto del archivo. Solo lectura String.

**Devuelve:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Devuelve la ruta completa a un archivo enlazado. Se usará el nombre largo del archivo. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Devueve la ruta completa a un archivo enlazado. Se usará el nombre largo del archivo. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Devuelve la ruta relativa a un archivo enlazado si está presente; de lo contrario, devuelve una cadena vacía. Solo lectura String.

--------------------

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


--------------------

En las presentaciones Ppt, algunos vínculos de objetos Ole pueden tener una representación relativa.

**Devuelve:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

Devuelve el nombre de archivo del objeto OLE incrustado

**Devuelve:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Devuelve la ruta del objeto OLE incrustado

**Devuelve:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Obtiene o establece información sobre datos OLE incrustados. Lectura/escritura [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Devuelve:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Establece información sobre datos OLE incrustados.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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
### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Determina si un objeto es visible como icono. Lectura/escritura boolean .

**Devuelve:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Determina si un objeto es visible como icono. Lectura/escritura boolean .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Determina si un objeto está enlazado a un archivo externo. Solo lectura boolean .

**Devuelve:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Determina si el objeto incrustado enlazado se actualiza automáticamente cuando la presentación se abre o se imprime. Lectura/escritura boolean .

**Devuelve:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Determina si el objeto incrustado enlazado se actualiza automáticamente cuando la presentación se abre o se imprime. Lectura/escritura boolean .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |