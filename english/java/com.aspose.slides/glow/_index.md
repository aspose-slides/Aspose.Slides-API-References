---
title: Glow
second_title: Aspose.Slides for Java API Reference
description:  Represents a Glow effect in which a color blurred outline 
 is added outside the edges of the object.
type: docs
weight: 222
url: /java/com.aspose.slides/glow/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Represents a Glow effect, in which a color blurred outline is added outside the edges of the object.
## Methods

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Color format. |
| [getEffective()](#getEffective--) | Gets effective Glow effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Glow](../../com.aspose.slides/glow) is equal to the current [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Radius. Read/write \`\`\` double \`\`\`.

**Returns:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Radius. Read/write \`\`\` double \`\`\`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Color format. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Gets effective Glow effect data with the inheritance applied.

**Returns:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Read-only long.

**Returns:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Returns parent IPresentationComponent. Read-only [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returns:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [Glow](../../com.aspose.slides/glow) is equal to the current [Glow](../../com.aspose.slides/glow).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [Glow](../../com.aspose.slides/glow) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
