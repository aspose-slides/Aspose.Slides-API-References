---
title: CommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents common slide view properties.
type: docs
url: /com.aspose.slides/commonslideviewproperties/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Represents common slide view properties.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Setting View Properties of Presentation
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Zoom value in percentages for slide view
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Zoom value in percentages for notes view
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getScale()](#getScale--) | Specifies the view scaling ratio in percentages. |
| [setScale(int value)](#setScale-int-) | Specifies the view scaling ratio in percentages. |
| [getVariableScale()](#getVariableScale--) | Specifies that the view content should automatically scale to best fit the current window size. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Specifies that the view content should automatically scale to best fit the current window size. |
### getScale() {#getScale--}
```
public final int getScale()
```


Specifies the view scaling ratio in percentages. Read/write int.

**Returns:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Specifies the view scaling ratio in percentages. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


Specifies that the view content should automatically scale to best fit the current window size. Read/write boolean.

**Returns:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


Specifies that the view content should automatically scale to best fit the current window size. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

