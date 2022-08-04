---
title: SmartArt
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a SmartArt diagram
type: docs
weight: 513
url: /java/com.aspose.slides/smartart/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

Represents a SmartArt diagram
## Constructors

| Constructor | Description |
| --- | --- |
| [SmartArt(IDOMObject parentImmediate)](#SmartArt-com.aspose.slides.IDOMObject-) |  |
| [SmartArt(IDOMObject parentImmediate, IPresentation presentation, int layoutType)](#SmartArt-com.aspose.slides.IDOMObject-com.aspose.slides.IPresentation-int-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Returns collections of all nodes in the SmartArt object. |
| [getNodes()](#getNodes--) | Returns collections of root nodes in SmartArt object. |
| [getLayout()](#getLayout--) | Returns or sets layout of the SmartArt object. |
| [setLayout(int value)](#setLayout-int-) | Returns or sets layout of the SmartArt object. |
| [getQuickStyle()](#getQuickStyle--) | Returns or sets quick style of SmartArt object. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Returns or sets quick style of SmartArt object. |
| [getColorStyle()](#getColorStyle--) | Returns or sets color style of SmartArt object. |
| [setColorStyle(int value)](#setColorStyle-int-) | Returns or sets color style of SmartArt object. |
| [isReversed()](#isReversed--) | Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. |
| [setReversed(boolean value)](#setReversed-boolean-) | Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. |
### SmartArt(IDOMObject parentImmediate) {#SmartArt-com.aspose.slides.IDOMObject-}
```
 SmartArt(IDOMObject parentImmediate)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### SmartArt(IDOMObject parentImmediate, IPresentation presentation, int layoutType) {#SmartArt-com.aspose.slides.IDOMObject-com.aspose.slides.IPresentation-int-}
```
 SmartArt(IDOMObject parentImmediate, IPresentation presentation, int layoutType)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |
| layoutType | int |  |

### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```


Returns collections of all nodes in the SmartArt object. Read-only [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```


Returns collections of root nodes in SmartArt object. Read-only [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public final int getLayout()
```


Returns or sets layout of the SmartArt object. Read/write [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Returns:**
int
### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```


Returns or sets layout of the SmartArt object. Read/write [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```


Returns or sets quick style of SmartArt object. Read/write [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Returns:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```


Returns or sets quick style of SmartArt object. Read/write [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```


Returns or sets color style of SmartArt object. Read/write [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Returns:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```


Returns or sets color style of SmartArt object. Read/write [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public final boolean isReversed()
```


Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. Read/write \`\`\` boolean \`\`\`.

**Returns:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```


Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. Read/write \`\`\` boolean \`\`\`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

