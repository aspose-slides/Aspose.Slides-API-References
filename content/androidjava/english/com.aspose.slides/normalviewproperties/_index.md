---
title: NormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /com.aspose.slides/normalviewproperties/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Represents normal view properties. The normal view consists of three content regions: the slide itself, a side content region, and a bottom content region.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Instantiate a presentation object that represents a presentation file
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. |
| [getVerticalBarState()](#getVerticalBarState--) | Specifies the state that the vertical splitter bar should be shown in. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Specifies the state that the vertical splitter bar should be shown in. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Specifies the state that the horizontal splitter bar should be shown in. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Specifies the state that the horizontal splitter bar should be shown in. |
| [getPreferSingleView()](#getPreferSingleView--) | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. |
| [getRestoredLeft()](#getRestoredLeft--) | This element specifies the sizing of the side content region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). |
| [getRestoredTop()](#getRestoredTop--) | This element specifies the sizing of the top slide region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```


Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. Read/write boolean.

**Returns:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```


Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```


Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. Read/write boolean.

**Returns:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```


Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```


Specifies the state that the vertical splitter bar should be shown in. A vertical splitter bar separates the slide from the side content region.

**Returns:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```


Specifies the state that the vertical splitter bar should be shown in. A vertical splitter bar separates the slide from the side content region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```


Specifies the state that the horizontal splitter bar should be shown in. A horizontal splitter bar separates the slide from the content region below the slide.

**Returns:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```


Specifies the state that the horizontal splitter bar should be shown in. A horizontal splitter bar separates the slide from the content region below the slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```


Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. If enabled, the application may choose to display one of the content regions in the entire window. Read/write boolean.

**Returns:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```


Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. If enabled, the application may choose to display one of the content regions in the entire window. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```


This element specifies the sizing of the side content region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). Read opnly [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returns:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```


This element specifies the sizing of the top slide region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). Read only [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returns:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
