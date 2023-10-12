---
title: PresentationAnimationsGenerator
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/presentationanimationsgenerator/
---

## PresentationAnimationsGenerator class

 Represents a generator of the animations in the  Presentation.
 
| Name | Description |
| --- | --- |
| PresentationAnimationsGenerator(Presentation(../presentation)) | Creates a new instance of the PresentationAnimationsGenerator. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation(../../presentation) | The frame size will be set with accordance to the ( Presentation#getSlideSize) |

### Result
PresentationAnimationsGenerator


---


| Name | Description |
| --- | --- |
| PresentationAnimationsGenerator(Dimension) | Creates a new instance of the PresentationAnimationsGenerator. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| frameSize | Dimension | The frame size. |

### Result
PresentationAnimationsGenerator


---


| Name | Description |
| --- | --- |
| PresentationAnimationsGenerator(Dimension2D) | Creates a new instance of the PresentationAnimationsGenerator. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| frameSize | Dimension2D | The frame size. |

### Result
PresentationAnimationsGenerator


---


| Name | Description |
| --- | --- |
| dispose () | Disposes the instance of the PresentationAnimationsGenerator. |


---


| Name | Description |
| --- | --- |
| getDefaultDelay () | Gets or sets default delay time [ms]. |

### Result
int


---


| Name | Description |
| --- | --- |
| getExportedSlides () | Get the number of the exported slides count. |

### Result
int


---


| Name | Description |
| --- | --- |
| getFrameSize () | Gets the frame size. |

### Result
Dimension


---


| Name | Description |
| --- | --- |
| getIncludeHiddenSlides () | Get or sets if hidden slides should be included. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| run (com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides. ISlide>) | Run the animation events generation for each slide. |


---


| Name | Description |
| --- | --- |
| run (com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides. ISlide>, int, PresentationPlayer.FrameTick(../presentationplayer.frametick)) | Run the animation events generation for each slide. |


---


| Name | Description |
| --- | --- |
| setDefaultDelay (int) | Gets or sets default delay time [ms]. |


---


| Name | Description |
| --- | --- |
| setIncludeHiddenSlides (boolean) | Get or sets if hidden slides should be included. |


---


| Name | Description |
| --- | --- |
| setNewAnimation (PresentationAnimationsGenerator.NewAnimation(../presentationanimationsgenerator.newanimation)) | Set a new animation event. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| anim | PresentationAnimationsGenerator.NewAnimation(../../presentationanimationsgenerator.newanimation) | Animation event. |


---


