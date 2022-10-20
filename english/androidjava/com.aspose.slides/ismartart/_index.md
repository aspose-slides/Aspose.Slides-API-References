---
title: ISmartArt
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a SmartArt diagram.
type: docs
weight: 1034
url: /androidjava/com.aspose.slides/ismartart/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Represents a SmartArt diagram.
## Methods

| Method | Description |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Returns collections of all nodes in SmartArt object. |
| [getNodes()](#getNodes--) | Returns collections of root nodes in SmartArt object. |
| [getLayout()](#getLayout--) | Return or set layout of the SmartArt object. |
| [setLayout(int value)](#setLayout-int-) | Return or set layout of the SmartArt object. |
| [getQuickStyle()](#getQuickStyle--) | Return or set quick style of the SmartArt object. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Return or set quick style of the SmartArt object. |
| [getColorStyle()](#getColorStyle--) | Return or set color style of the SmartArt object. |
| [setColorStyle(int value)](#setColorStyle-int-) | Return or set color style of the SmartArt object. |
| [isReversed()](#isReversed--) | Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. |
| [setReversed(boolean value)](#setReversed-boolean-) | Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Returns collections of all nodes in SmartArt object. Read-only [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


Returns collections of root nodes in SmartArt object. Read-only [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Return or set layout of the SmartArt object. Read/write [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Returns:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Return or set layout of the SmartArt object. Read/write [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Return or set quick style of the SmartArt object. Read/write [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Returns:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Return or set quick style of the SmartArt object. Read/write [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Return or set color style of the SmartArt object. Read/write [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Returns:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Return or set color style of the SmartArt object. Read/write [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. Read/write boolean.

**Returns:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

