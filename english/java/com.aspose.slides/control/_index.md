---
title: Control
second_title: Aspose.Slides for Java API Reference
description: Represents an ActiveX control.
type: docs
weight: 136
url: /java/com.aspose.slides/control/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Represents an ActiveX control.
## Methods

| Method | Description |
| --- | --- |
| [getPersistence()](#getPersistence--) | Gets the method used to store properties of the ActiveX control. |
| [getName()](#getName--) | Gets or sets the name of this control. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the name of this control. |
| [getClassId()](#getClassId--) | Gets class id of this control. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Gets class id of this control. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returns Control image fill properties object. |
| [getFrame()](#getFrame--) | Returns or sets control's frame. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returns or sets control's frame. |
| [getProperties()](#getProperties--) | Returns a collection of ActiveX properties. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```


Gets the method used to store properties of the ActiveX control. Read only [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Use your own method for managing ActiveX properties stored in its binary file
>  }
> ```

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Gets or sets the name of this control. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets the name of this control. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```


Gets class id of this control. Read-only java.util.UUID.

**Returns:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```


Gets class id of this control. Read-only java.util.UUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


Returns Control image fill properties object. Read-only [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```


Returns or sets control's frame. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```


Returns or sets control's frame. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```


Returns a collection of ActiveX properties. Read-only [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Note: Aspose.Slides supports only XML based ActiveX properties. If properties stored in binary format, this property will return null.

**Returns:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```


Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Use your own method for managing ActiveX properties stored in its binary file
>  }
> ```

**Returns:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the base slide. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the presentation. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
