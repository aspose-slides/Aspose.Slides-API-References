---
title: OleObjectFrame
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un objet OLE sur une diapositive.
type: docs
url: /fr/com.aspose.slides/oleobjectframe/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Représente un objet OLE sur une diapositive.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Charge le PPTX dans un objet Presentation
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Accède à la première diapositive
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Convertit la forme en OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Lit l'objet OLE et l'écrit sur le disque
>      if (oleObjectFrame != null) {
>          // Obtient les données du fichier incorporé
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Obtient l'extension du fichier incorporé
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Crée un chemin pour sauvegarder le fichier extrait
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Enregistre les données extraites
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Renvoie l'objet de propriétés de remplissage d'image OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Renvoie ou définit le titre de l'icône OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Renvoie ou définit le titre de l'icône OleObject. |
| [getObjectName()](#getObjectName--) | Renvoie ou définit le nom d'un objet. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Renvoie ou définit le nom d'un objet. |
| [getObjectProgId()](#getObjectProgId--) | Renvoie le ProgID d'un objet. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Renvoie le ProgID d'un objet. |
| [getLinkFileName()](#getLinkFileName--) | Renvoie le chemin complet d'un fichier lié. |
| [getLinkPathLong()](#getLinkPathLong--) | Renvoie le chemin complet d'un fichier lié. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Renvoie le chemin complet d'un fichier lié. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Renvoie le chemin relatif d'un fichier lié s'il est présent, sinon renvoie une chaîne vide. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Renvoie le nom de fichier de l'objet OLE incorporé |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Renvoie le chemin de l'objet OLE incorporé |
| [getEmbeddedData()](#getEmbeddedData--) | Obtient ou définit les informations sur les données OLE incorporées. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Définit les informations sur les données OLE incorporées. |
| [isObjectIcon()](#isObjectIcon--) | Détermine si un objet est visible sous forme d'icône. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Détermine si un objet est visible sous forme d'icône. |
| [isObjectLink()](#isObjectLink--) | Détermine si un objet est lié à un fichier externe. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Détermine si l'objet incorporé lié est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Détermine si l'objet incorporé lié est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Renvoie l'objet de propriétés de remplissage d'image OleObject. Lecture seule [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Renvoie :**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Renvoie ou définit le titre de l'icône OleObject. Lecture/écriture String.

--------------------

Lorsque IsObjectIcon == false, cette valeur est ignorée. La chaîne peut être tronquée en fonction de la taille de l'icône Ole.

**Renvoie :**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Renvoie ou définit le titre de l'icône OleObject. Lecture/écriture String.

--------------------

Lorsque IsObjectIcon == false, cette valeur est ignorée. La chaîne peut être tronquée en fonction de la taille de l'icône Ole.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Renvoie ou définit le nom d'un objet. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Renvoie ou définit le nom d'un objet. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Renvoie le ProgID d'un objet. Lecture seule String.

**Renvoie :**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Renvoie le ProgID d'un objet. Lecture seule String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Renvoie le chemin complet d'un fichier lié. Le nom de fichier court sera utilisé. Lecture seule String.

**Renvoie :**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Renvoie le chemin complet d'un fichier lié. Le nom de fichier long sera utilisé. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Renvoie le chemin complet d'un fichier lié. Le nom de fichier long sera utilisé. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Renvoie le chemin relatif d'un fichier lié s'il est présent, sinon renvoie une chaîne vide. Lecture seule String.

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

Dans les présentations Ppt, certains liens d'objets Ole peuvent avoir une représentation relative.

**Renvoie :**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

Renvoie le nom de fichier de l'objet OLE incorporé

**Renvoie :**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Renvoie le chemin de l'objet OLE incorporé

**Renvoie :**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Obtient ou définit les informations sur les données OLE incorporées. Lecture/écriture [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Renvoie :**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Définit les informations sur les données OLE incorporées.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Données incorporées [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

Cette méthode modifie les propriétés de l'objet pour refléter les nouvelles données et définit le drapeau IsObjectLink sur false, indiquant que l'objet OLE est incorporé. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Détermine si un objet est visible sous forme d'icône. Lecture/écriture boolean.

**Renvoie :**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Détermine si un objet est visible sous forme d'icône. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Détermine si un objet est lié à un fichier externe. Lecture seule boolean.

**Renvoie :**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Détermine si l'objet incorporé lié est mis à jour automatiquement lorsque la présentation est ouverte ou imprimée. Lecture/écriture boolean.

**Renvoie :**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Détermine si l'objet incorporé lié est mis à jour automatiquement lorsque la présentation est ouverte ou imprimée. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
