---
title: CommonSlideViewProperties
second_title: Aspose.Slides for Java API Reference
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
| [getDrawingGuides()](#getDrawingGuides--) | Returns the collection of the drawing guides. |
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

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Returns the collection of the drawing guides. Read-only [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Adding the new horizontal drawing guide below the slide center
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
