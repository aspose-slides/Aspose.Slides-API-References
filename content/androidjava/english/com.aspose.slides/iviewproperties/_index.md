---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Presentation wide view properties.
type: docs
url: /com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Presentation wide view properties.
## Methods

| Method | Description |
| --- | --- |
| [getLastView()](#getLastView--) | Specifies the view mode that was used when the presentation document was last saved. |
| [setLastView(int value)](#setLastView-int-) | Specifies the view mode that was used when the presentation document was last saved. |
| [getShowComments()](#getShowComments--) | Specifies whether the slide comments should be shown. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specifies whether the slide comments should be shown. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specifies common view properties associated with the slide view mode. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specifies common view properties associated with the notes view mode. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Represents normal view properties. |
| [getGridSpacing()](#getGridSpacing--) | Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```


Specifies the view mode that was used when the presentation document was last saved. Read/write [ViewType](../../com.aspose.slides/viewtype).

**Returns:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```


Specifies the view mode that was used when the presentation document was last saved. Read/write [ViewType](../../com.aspose.slides/viewtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```


Specifies whether the slide comments should be shown. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```


Specifies whether the slide comments should be shown. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```


Specifies common view properties associated with the slide view mode. Read-only [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```


Specifies common view properties associated with the notes view mode. Read-only [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```


Represents normal view properties. The normal view consists of three content regions: the slide itself, a side content region, and a bottom content region. Read-only [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Returns:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```


Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. Read/write float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

The grid spacing value must be a positive number. The typical value range is from 1 mm (2.8349607 points) to 2 inches (144 points).

**Returns:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```


Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. Read/write float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

The grid spacing value must be a positive number. The typical value range is from 1 mm (2.8349607 points) to 2 inches (144 points).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

