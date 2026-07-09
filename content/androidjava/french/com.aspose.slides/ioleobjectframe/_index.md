---
title: IOleObjectFrame
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un objet OLE sur une diapositive.
type: docs
url: /fr/com.aspose.slides/ioleobjectframe/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Représente un objet OLE sur une diapositive.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Renvoie l'objet OleObject des propriétés de remplissage d'image. |
| [getObjectName()](#getObjectName--) | Renvoie ou définit le nom d'un objet. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Renvoie ou définit le nom d'un objet. |
| [getEmbeddedData()](#getEmbeddedData--) | Obtient des informations sur les données OLE intégrées. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Définit les informations sur les données OLE intégrées. |
| [getObjectProgId()](#getObjectProgId--) | Renvoie le ProgID d'un objet. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Renvoie le ProgID d'un objet. |
| [getLinkFileName()](#getLinkFileName--) | Renvoie le chemin complet d'un fichier lié. |
| [getLinkPathLong()](#getLinkPathLong--) | Renvoie le chemin complet d'un fichier lié. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Renvoie le chemin complet d'un fichier lié. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Renvoie le chemin relatif d'un fichier lié s'il est présent, sinon renvoie une chaîne vide. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Renvoie le nom de fichier de l'objet OLE intégré |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Renvoie le chemin de l'objet OLE intégré |
| [isObjectIcon()](#isObjectIcon--) | Détermine si un objet est visible sous forme d'icône. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Détermine si un objet est visible sous forme d'icône. |
| [isObjectLink()](#isObjectLink--) | Détermine si un objet est lié à un fichier externe. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Détermine si l'objet intégré lié est mis à jour automatiquement lorsque la présentation est ouverte ou imprimée. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Détermine si l'objet intégré lié est mis à jour automatiquement lorsque la présentation est ouverte ou imprimée. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Renvoie ou définit le titre de l'icône OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Renvoie ou définit le titre de l'icône OleObject. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Renvoie l'objet OleObject des propriétés de remplissage d'image. Lecture seule [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Renvoie :**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Renvoie ou définit le nom d'un objet. Lecture/écriture String.

**Renvoie :**  
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Renvoie ou définit le nom d'un objet. Lecture/écriture String.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Obtient des informations sur les données OLE intégrées. Lecture seule [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Renvoie :**  
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Définit les informations sur les données OLE intégrées.

--------------------

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

This method changes the properties of the object to reflect the new data and sets the IsObjectLink flag to false, indicating that the OLE object is embedded. |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Returns the ProgID of an object. Read olny String.

**Returns:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Returns the ProgID of an object. Read olny String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Returns the full path to a linked file. Short file name will be used. Read-only String.

**Returns:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Returns the full path to a linked file. Long file name will be used. Read/write String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Returns the full path to a linked file. Long file name will be used. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Returns the relative path to a linked file if present, otherwise returns an empty string. Readonly String.

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

In the Ppt presentations, some Ole object links may have a relative representation.

**Returns:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Returns the file name of embedded OLE object

**Returns:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Returns the path of embedded OLE object

**Returns:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Determines whether an object is visible as icon. Read/write boolean.

**Returns:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Determines whether an object is visible as icon. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Determines whether an object is linked to external file. Read-only boolean.

**Returns:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write boolean.

**Returns:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Returns or sets the title for OleObject icon. Read/write String.

--------------------

When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the OLE icon.

**Returns:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)

Renvoie ou définit le titre de l'icône OleObject. Lecture/écriture String.

--------------------

Lorsque IsObjectIcon == false, cette valeur est ignorée. La chaîne peut être tronquée en fonction de la taille de l'icône OLE.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |