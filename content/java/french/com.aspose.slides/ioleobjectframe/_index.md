---
title: IOleObjectFrame
second_title: Référence de l'API Aspose.Slides for Java
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
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Renvoie l'objet des propriétés de remplissage d'image OleObject. |
| [getObjectName()](#getObjectName--) | Renvoie ou définit le nom d'un objet. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Renvoie ou définit le nom d'un objet. |
| [getEmbeddedData()](#getEmbeddedData--) | Obtient les informations sur les données OLE intégrées. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Définit les informations sur les données OLE intégrées. |
| [getObjectProgId()](#getObjectProgId--) | Renvoie le ProgID d'un objet. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Renvoie le ProgID d'un objet. |
| [getLinkFileName()](#getLinkFileName--) | Renvoie le chemin complet d'un fichier lié. |
| [getLinkPathLong()](#getLinkPathLong--) | Renvoie le chemin complet d'un fichier lié. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Renvoie le chemin complet d'un fichier lié. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Renvoie le chemin relatif d'un fichier lié s'il est présent, sinon renvoie une chaîne vide. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Renvoie le nom de fichier de l'objet OLE intégré. |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Renvoie le chemin de l'objet OLE intégré. |
| [isObjectIcon()](#isObjectIcon--) | Détermine si un objet est visible sous forme d'icône. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Détermine si un objet est visible sous forme d'icône. |
| [isObjectLink()](#isObjectLink--) | Détermine si un objet est lié à un fichier externe. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Détermine si l'objet intégré lié est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Détermine si l'objet intégré lié est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Renvoie ou définit le titre de l'icône OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Renvoie ou définit le titre de l'icône OleObject. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Renvoie l'objet des propriétés de remplissage d'image OleObject. Lecture seule [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

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


Obtient les informations sur les données OLE intégrées. Lecture seule [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Données intégrées [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Cette méthode modifie les propriétés de l'objet pour refléter les nouvelles données et définit le drapeau IsObjectLink sur false, indiquant que l'objet OLE est intégré. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```


Renvoie le ProgID d'un objet. Lecture seule String.

**Renvoie :**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```


Renvoie le ProgID d'un objet. Lecture seule String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


Renvoie le chemin complet d'un fichier lié. Le nom de fichier court sera utilisé. Lecture seule String.

**Renvoie :**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Renvoie le chemin complet d'un fichier lié. Le nom de fichier long sera utilisé. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Renvoie le chemin complet d'un fichier lié. Le nom de fichier long sera utilisé. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
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

Dans les présentations PPT, certains liens d'objets Ole peuvent avoir une représentation relative.

**Renvoie :**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```


Renvoie le nom de fichier de l'objet OLE intégré

**Renvoie :**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```


Renvoie le chemin de l'objet OLE intégré

**Renvoie :**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```


Détermine si un objet est visible sous forme d'icône. Lecture/écriture boolean.

**Renvoie :**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```


Détermine si un objet est visible sous forme d'icône. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```


Détermine si un objet est lié à un fichier externe. Lecture seule boolean.

**Renvoie :**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


Détermine si l'objet intégré lié est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée. Lecture/écriture boolean.

**Renvoie :**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


Détermine si l'objet intégré lié est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


Renvoie ou définit le titre de l'icône OleObject. Lecture/écriture String.

--------------------

Lorsque IsObjectIcon == false, cette valeur est ignorée. La chaîne peut être tronquée en fonction de la taille de l'icône OLE.

**Renvoie :**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


Renvoie ou définit le titre de l'icône OleObject. Lecture/écriture String.

--------------------

Lorsque IsObjectIcon == false, cette valeur est ignorée. La chaîne peut être tronquée en fonction de la taille de l'icône OLE.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |