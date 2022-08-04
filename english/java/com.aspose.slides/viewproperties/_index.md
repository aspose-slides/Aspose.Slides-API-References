---
title: ViewProperties
second_title: Aspose.Sildes for Java API Reference
description: p
 Presentation wide view properties.
type: docs
weight: 608
url: /java/com.aspose.slides/viewproperties/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Presentation wide view properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [ViewProperties(Presentation parentImmediate)](#ViewProperties-com.aspose.slides.Presentation-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLastView()](#getLastView--) | Specifies the view mode that was used when the presentation document was last saved. |
| [setLastView(int value)](#setLastView-int-) | Specifies the view mode that was used when the presentation document was last saved. |
| [getShowComments()](#getShowComments--) | Specifies whether the slide comments should be shown. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specifies whether the slide comments should be shown. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Represents normal view properties. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specifies common view properties associated with the slide view mode. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specifies common view properties associated with the notes view mode. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### ViewProperties(Presentation parentImmediate) {#ViewProperties-com.aspose.slides.Presentation-}
```
 ViewProperties(Presentation parentImmediate)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [Presentation](../../com.aspose.slides/presentation) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```


Specifies the view mode that was used when the presentation document was last saved. Read/write [ViewType](../../com.aspose.slides/viewtype).

**Returns:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```


Specifies the view mode that was used when the presentation document was last saved. Read/write [ViewType](../../com.aspose.slides/viewtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```


Specifies whether the slide comments should be shown. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```


Specifies whether the slide comments should be shown. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```


Represents normal view properties. The normal view consists of three content regions: the slide itself, a side content region, and a bottom content region. Read-only [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Returns:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```


Specifies common view properties associated with the slide view mode. Read-only [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```


Specifies common view properties associated with the notes view mode. Read-only [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
