---
title: Control
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/control/
---
## Control classe

 Représente un contrôle ActiveX.
 
### getActiveXControlBinary {#getActiveXControlBinary}

| Nom | Description |
| --- | --- |
| getActiveXControlBinary () | Spécifie la persistance d'un contrôle ActiveX lorsque la méthode utilisée pour persister est soit PersistStream, PersistStreamInit ou PersistStorage. |

 **Retour:**  
byte


---


### getClassId {#getClassId}

| Nom | Description |
| --- | --- |
| getClassId () | Obtient l'identifiant de classe de ce contrôle. Lecture seule java.util.UUID. |

 **Retour:**  
UUID


---


### getFrame {#getFrame}

| Nom | Description |
| --- | --- |
| getFrame () | Renvoie ou définit le cadre du contrôle. Lecture/écriture IShapeFrame. |

 **Retour:**  
[ShapeFrame](../shapeframe)


---


### getName {#getName}

| Nom | Description |
| --- | --- |
| getName () | Obtient ou définit le nom de ce contrôle. Lecture/écriture String. |

 **Retour:**  
String


---


### getPersistence {#getPersistence}

| Nom | Description |
| --- | --- |
| getPersistence () | Obtient la méthode utilisée pour stocker les propriétés du contrôle ActiveX. Lecture seule PersistenceType. |

 **Retour:**  
int


---


### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () |  |

 **Retour:**  
[Presentation](../presentation)


---


### getProperties {#getProperties}

| Nom | Description |
| --- | --- |
| getProperties () | Renvoie une collection de propriétés ActiveX. Lecture seule IControlPropertiesCollection. Remarque : Aspose.Slides prend en charge uniquement les propriétés ActiveX basées sur XML. Si les propriétés sont stockées au format binaire, cette propriété renverra null. |

 **Retour:**  
[ControlPropertiesCollection](../controlpropertiescollection)


---


### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () |  |

 **Retour:**  
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSubstitutePictureFormat {#getSubstitutePictureFormat}

| Nom | Description |
| --- | --- |
| getSubstitutePictureFormat () | Renvoie l'objet des propriétés de remplissage d'image du contrôle. Lecture seule IPictureFillFormat. |

 **Retour:**  
[PictureFillFormat](../picturefillformat)


---


### setClassId {#setClassId}

| Nom | Description |
| --- | --- |
| setClassId (UUID) | Obtient l'identifiant de classe de ce contrôle. Lecture seule java.util.UUID. |

 **Retour:**  
void


---


### setFrame {#setFrame}

| Nom | Description |
| --- | --- |
| setFrame ([ShapeFrame](../shapeframe)) | Renvoie ou définit le cadre du contrôle. Lecture/écriture IShapeFrame. |

 **Retour:**  
void


---


### setName {#setName}

| Nom | Description |
| --- | --- |
| setName (String) | Obtient ou définit le nom de ce contrôle. Lecture/écriture String. |

 **Retour:**  
void


---