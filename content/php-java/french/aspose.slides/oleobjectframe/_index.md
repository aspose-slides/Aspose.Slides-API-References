---
title: OleObjectFrame
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/oleobjectframe/
---
## OleObjectFrame classe

 Représente un objet OLE sur une diapositive.
 
### getEmbeddedData {#getEmbeddedData}

| Nom | Description |
| --- | --- |
| getEmbeddedData () | Obtient ou définit les informations sur les données OLE incorporées. Lecture/écriture IOleEmbeddedDataInfo. |

 **Retourne :**
[OleEmbeddedDataInfo](../oleembeddeddatainfo)


---


### getEmbeddedFileLabel {#getEmbeddedFileLabel}

| Nom | Description |
| --- | --- |
| getEmbeddedFileLabel () | Renvoie le nom de fichier de l'objet OLE incorporé |

 **Retourne :**
String


---


### getEmbeddedFileName {#getEmbeddedFileName}

| Nom | Description |
| --- | --- |
| getEmbeddedFileName () | Renvoie le chemin de l'objet OLE incorporé |

 **Retourne :**
String


---


### getLinkFileName {#getLinkFileName}

| Nom | Description |
| --- | --- |
| getLinkFileName () | Renvoie le chemin complet d'un fichier lié. Le nom de fichier court sera utilisé. Lecture seule String. |

 **Retourne :**
String


---


### getLinkPathLong {#getLinkPathLong}

| Nom | Description |
| --- | --- |
| getLinkPathLong () | Renvoie le chemin complet d'un fichier lié. Un nom de fichier long sera utilisé. Lecture/écriture String. |

 **Retourne :**
String


---


### getLinkPathRelative {#getLinkPathRelative}

| Nom | Description |
| --- | --- |
| getLinkPathRelative () | Renvoie le chemin relatif d'un fichier lié s'il existe, sinon renvoie une chaîne vide. Lecture seule String. Dans les présentations Ppt, certains liens d'objets Ole peuvent avoir une représentation relative. |

 **Retourne :**
String


---


### getObjectName {#getObjectName}

| Nom | Description |
| --- | --- |
| getObjectName () | Obtient ou définit le nom d'un objet. Lecture/écriture String. |

 **Retourne :**
String


---


### getObjectProgId {#getObjectProgId}

| Nom | Description |
| --- | --- |
| getObjectProgId () | Renvoie le ProgID d'un objet. Lecture seule String. |

 **Retourne :**
String


---


### getSubstitutePictureFormat {#getSubstitutePictureFormat}

| Nom | Description |
| --- | --- |
| getSubstitutePictureFormat () | Renvoie l'objet des propriétés de remplissage d'image OleObject. Lecture seule IPictureFillFormat. |

 **Retourne :**
[PictureFillFormat](../picturefillformat)


---


### getSubstitutePictureTitle {#getSubstitutePictureTitle}

| Nom | Description |
| --- | --- |
| getSubstitutePictureTitle () | Obtient ou définit le titre pour l'icône OleObject. Lecture/écriture String. Lorsque IsObjectIcon == false cette valeur est ignorée. La chaîne peut être tronquée en fonction de la taille de l'icône Ole. |

 **Retourne :**
String


---


### getUpdateAutomatic {#getUpdateAutomatic}

| Nom | Description |
| --- | --- |
| getUpdateAutomatic () | Détermine si l'objet lié incorporé est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée. Lecture/écriture boolean. |

 **Retourne :**
boolean


---


### isObjectIcon {#isObjectIcon}

| Nom | Description |
| --- | --- |
| isObjectIcon () | Détermine si un objet est visible sous forme d'icône. Lecture/écriture boolean. |

 **Retourne :**
boolean


---


### isObjectLink {#isObjectLink}

| Nom | Description |
| --- | --- |
| isObjectLink () | Détermine si un objet est lié à un fichier externe. Lecture seule boolean. |

 **Retourne :**
boolean


---


### setEmbeddedData {#setEmbeddedData}

| Nom | Description |
| --- | --- |
| setEmbeddedData ([OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Définit les informations sur les données OLE incorporées. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| embeddedData | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | Données incorporées IOleEmbeddedDataInfo Cette méthode modifie les propriétés de l'objet pour refléter les nouvelles données et définit le drapeau IsObjectLink à false, indiquant que l'objet OLE est incorporé. |

 **Retourne :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentNullException | Lorsque le paramètre embeddedData est nul. |


---


### setLinkPathLong {#setLinkPathLong}

| Nom | Description |
| --- | --- |
| setLinkPathLong (String) | Renvoie le chemin complet d'un fichier lié. Un nom de fichier long sera utilisé. Lecture/écriture String. |

 **Retourne :**
void


---


### setObjectIcon {#setObjectIcon}

| Nom | Description |
| --- | --- |
| setObjectIcon (boolean) | Détermine si un objet est visible sous forme d'icône. Lecture/écriture boolean. |

 **Retourne :**
void


---


### setObjectName {#setObjectName}

| Nom | Description |
| --- | --- |
| setObjectName (String) | Obtient ou définit le nom d'un objet. Lecture/écriture String. |

 **Retourne :**
void


---


### setObjectProgId {#setObjectProgId}

| Nom | Description |
| --- | --- |
| setObjectProgId (String) | Renvoie le ProgID d'un objet. Lecture seule String. |

 **Retourne :**
void


---


### setSubstitutePictureTitle {#setSubstitutePictureTitle}

| Nom | Description |
| --- | --- |
| setSubstitutePictureTitle (String) | Obtient ou définit le titre pour l'icône OleObject. Lecture/écriture String. Lorsque IsObjectIcon == false cette valeur est ignorée. La chaîne peut être tronquée en fonction de la taille de l'icône Ole. |

 **Retourne :**
void


---


### setUpdateAutomatic {#setUpdateAutomatic}

| Nom | Description |
| --- | --- |
| setUpdateAutomatic (boolean) | Détermine si l'objet lié incorporé est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée. Lecture/écriture boolean. |

 **Retourne :**
void


---