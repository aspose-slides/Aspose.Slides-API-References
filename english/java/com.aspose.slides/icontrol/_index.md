---
title: IControl
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents an ActiveX control.
type: docs
weight: 729
url: /java/com.aspose.slides/icontrol/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Represents an ActiveX control.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns the name of this control. |
| [setName(String value)](#setName-java.lang.String-) | Returns the name of this control. |
| [getClassId()](#getClassId--) | Gets class id of this control. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returns ControlEx image fill properties object. |
| [getFrame()](#getFrame--) | Returns or sets control's frame. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returns or sets control's frame. |
| [getProperties()](#getProperties--) | Returns a collection of ActiveX properties. |
| [getPersistence()](#getPersistence--) | Gets the method used to store properties of the ActiveX control. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```


Returns the name of this control. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Returns the name of this control. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```


Gets class id of this control. Read-only java.util.UUID.

**Returns:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Returns ControlEx image fill properties object. Read-only [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


Returns or sets control's frame. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```


Returns or sets control's frame. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```


Returns a collection of ActiveX properties. Read-only [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Returns:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```


Gets the method used to store properties of the ActiveX control. Read only [PersistenceType](../../com.aspose.slides/persistencetype).

**Returns:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```


Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage.

**Returns:**
byte[]
