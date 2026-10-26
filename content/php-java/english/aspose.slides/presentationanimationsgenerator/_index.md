---
title: PresentationAnimationsGenerator
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/presentationanimationsgenerator/
---

## PresentationAnimationsGenerator class

 Represents a generator of the animations in the  Presentation.
 
### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| Name | Description |
| --- | --- |
| PresentationAnimationsGenerator([Presentation](../presentation)) | Creates a new instance of the PresentationAnimationsGenerator. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | The frame size will be set with accordance to the Presentation#getSlideSize |

 **Returns:**
PresentationAnimationsGenerator


---


### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| Name | Description |
| --- | --- |
| PresentationAnimationsGenerator(Dimension) | Creates a new instance of the PresentationAnimationsGenerator. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| frameSize | Dimension | The frame size. |

 **Returns:**
PresentationAnimationsGenerator


---


### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| Name | Description |
| --- | --- |
| PresentationAnimationsGenerator(Dimension2D) | Creates a new instance of the PresentationAnimationsGenerator. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| frameSize | Dimension2D | The frame size. |

 **Returns:**
PresentationAnimationsGenerator


---


### dispose {#dispose}

| Name | Description |
| --- | --- |
| dispose () | Disposes the instance of the PresentationAnimationsGenerator. |

 **Returns:**
void


---


### getDefaultDelay {#getDefaultDelay}

| Name | Description |
| --- | --- |
| getDefaultDelay () | Gets or sets default delay time [ms]. |

 **Returns:**
int


---


### getExportedSlides {#getExportedSlides}

| Name | Description |
| --- | --- |
| getExportedSlides () | Get the number of the exported slides count. |

 **Returns:**
int


---


### getFrameSize {#getFrameSize}

| Name | Description |
| --- | --- |
| getFrameSize () | Gets the frame size. |

 **Returns:**
Dimension


---


### getIncludeHiddenSlides {#getIncludeHiddenSlides}

| Name | Description |
| --- | --- |
| getIncludeHiddenSlides () | Get or sets if hidden slides should be included. |

 **Returns:**
boolean


---


### run {#run}

| Name | Description |
| --- | --- |
| run (com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides. ISlide>) | Run the animation events generation for each slide. |

 **Returns:**
void


---


### run {#run}

| Name | Description |
| --- | --- |
| run (com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides. ISlide>, int, [PresentationPlayer.FrameTick](../presentationplayer.frametick)) | Run the animation events generation for each slide. |

 **Returns:**
void


---


### setDefaultDelay {#setDefaultDelay}

| Name | Description |
| --- | --- |
| setDefaultDelay (int) | Gets or sets default delay time [ms]. |

 **Returns:**
void


---


### setIncludeHiddenSlides {#setIncludeHiddenSlides}

| Name | Description |
| --- | --- |
| setIncludeHiddenSlides (boolean) | Get or sets if hidden slides should be included. |

 **Returns:**
void


---


### setNewAnimation {#setNewAnimation}

| Name | Description |
| --- | --- |
| setNewAnimation ([PresentationAnimationsGenerator.NewAnimation](../presentationanimationsgenerator.newanimation)) | Set a new animation event. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| anim | [PresentationAnimationsGenerator.NewAnimation](../presentationanimationsgenerator.newanimation) | Animation event. |

 **Returns:**
void


---


