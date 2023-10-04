---
title: Control
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/control/
---

## Control class

 Represents an ActiveX control.
 

## Functions

| Name | Description |
| --- | --- |
| [getActiveXControlBinary]() | Specifies the persistence of an ActiveX control when the function used to persist is either PersistStream, PersistStreamInit or PersistStorage. |

### Result
byte


---


| [getClassId]() | Gets class id of this control. Read-only java.util.UUID. |

### Result
UUID


---


| [getFrame]() | Returns or sets control's frame. Read/write IShapeFrame. |

### Result
[ShapeFrame](../../shapeframe)


---


| [getName]() | Gets or sets the name of this control. Read/write String. |

### Result
String


---


| [getPersistence]() | Gets the function used to store properties of the ActiveX control. Read only PersistenceType. |

### Result
int


---


| [getPresentation]() |  |

### Result
[Presentation](../../presentation)


---


| [getProperties]() | Returns a collection of ActiveX properties. Read-only IControlPropertiesCollection. Note: Aspose.Slides supports only XML based ActiveX properties. If properties stored in binary format, this property will return null. |

### Result
[ControlPropertiesCollection](../../controlpropertiescollection)


---


| [getSlide]() |  |

### Result
[MasterNotesSlide](../../masternotesslide), [MasterHandoutSlide](../../masterhandoutslide), [BaseSlide](../../baseslide), [NotesSlide](../../notesslide), [LayoutSlide](../../layoutslide), [Slide](../../slide), [MasterSlide](../../masterslide)


---


| [getSubstitutePictureFormat]() | Returns Control image fill properties object. Read-only IPictureFillFormat. |

### Result
[PictureFillFormat](../../picturefillformat)


---


| [setClassId](UUID) | Gets class id of this control. Read-only java.util.UUID. |


---


| [setFrame]([ShapeFrame](../shapeframe)) | Returns or sets control's frame. Read/write IShapeFrame. |


---


| [setName](String) | Gets or sets the name of this control. Read/write String. |


---


