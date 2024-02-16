---
title: Control
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/control/
---

## Control class

 Represents an ActiveX control.
 
### getActiveXControlBinary {#getActiveXControlBinary}

| Name | Description |
| --- | --- |
| getActiveXControlBinary () | Specifies the persistence of an ActiveX control when the function used to persist is either PersistStream, PersistStreamInit or PersistStorage. |

 **Result:**
byte


---


### getClassId {#getClassId}

| Name | Description |
| --- | --- |
| getClassId () | Gets class id of this control. Read-only java.util.UUID. |

 **Result:**
UUID


---


### getFrame {#getFrame}

| Name | Description |
| --- | --- |
| getFrame () | Returns or sets control's frame. Read/write IShapeFrame. |

 **Result:**
[ShapeFrame](../shapeframe)


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName () | Gets or sets the name of this control. Read/write String. |

 **Result:**
String


---


### getPersistence {#getPersistence}

| Name | Description |
| --- | --- |
| getPersistence () | Gets the function used to store properties of the ActiveX control. Read only PersistenceType. |

 **Result:**
int


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () |  |

 **Result:**
[Presentation](../presentation)


---


### getProperties {#getProperties}

| Name | Description |
| --- | --- |
| getProperties () | Returns a collection of ActiveX properties. Read-only IControlPropertiesCollection. Note: Aspose.Slides supports only XML based ActiveX properties. If properties stored in binary format, this property will return null. |

 **Result:**
[ControlPropertiesCollection](../controlpropertiescollection)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () |  |

 **Result:**
[NotesSlide](../notesslide), [MasterHandoutSlide](../masterhandoutslide), [LayoutSlide](../layoutslide), [MasterSlide](../masterslide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [Slide](../slide)


---


### getSubstitutePictureFormat {#getSubstitutePictureFormat}

| Name | Description |
| --- | --- |
| getSubstitutePictureFormat () | Returns Control image fill properties object. Read-only IPictureFillFormat. |

 **Result:**
[PictureFillFormat](../picturefillformat)


---


### setClassId {#setClassId}

| Name | Description |
| --- | --- |
| setClassId (UUID) | Gets class id of this control. Read-only java.util.UUID. |


---


### setFrame {#setFrame}

| Name | Description |
| --- | --- |
| setFrame ([ShapeFrame](../shapeframe)) | Returns or sets control's frame. Read/write IShapeFrame. |


---


### setName {#setName}

| Name | Description |
| --- | --- |
| setName (String) | Gets or sets the name of this control. Read/write String. |


---


