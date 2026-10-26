---
title: PresentationAnimationsGenerator
second_title: Aspose.Sildes για PHP μέσω αναφοράς Java API
description: 
type: docs

url: /el/aspose.slides/presentationanimationsgenerator/
---
## PresentationAnimationsGenerator κλάση

Αναπαριστά έναν δημιουργό των κινούμενων εικόνων στην Presentation.
 
### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| Όνομα | Περιγραφή |
| --- | --- |
| PresentationAnimationsGenerator([Presentation](../presentation)) | Creates a new instance of the PresentationAnimationsGenerator. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | The frame size will be set with accordance to the Presentation#getSlideSize |

 **Επιστρέφει:**
PresentationAnimationsGenerator


---

### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| Όνομα | Περιγραφή |
| --- | --- |
| PresentationAnimationsGenerator(Dimension) | Creates a new instance of the PresentationAnimationsGenerator. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| frameSize | Dimension | The frame size. |

 **Επιστρέφει:**
PresentationAnimationsGenerator


---

### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| Όνομα | Περιγραφή |
| --- | --- |
| PresentationAnimationsGenerator(Dimension2D) | Creates a new instance of the PresentationAnimationsGenerator. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| frameSize | Dimension2D | The frame size. |

 **Επιστρέφει:**
PresentationAnimationsGenerator


---

### dispose {#dispose}

| Όνομα | Περιγραφή |
| --- | --- |
| dispose () | Disposes the instance of the PresentationAnimationsGenerator. |

 **Επιστρέφει:**
void


---

### getDefaultDelay {#getDefaultDelay}

| Όνομα | Περιγραφή |
| --- | --- |
| getDefaultDelay () | Gets or sets default delay time [ms]. |

 **Επιστρέφει:**
int


---

### getExportedSlides {#getExportedSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| getExportedSlides () | Get the number of the exported slides count. |

 **Επιστρέφει:**
int


---

### getFrameSize {#getFrameSize}

| Όνομα | Περιγραφή |
| --- | --- |
| getFrameSize () | Gets the frame size. |

 **Επιστρέφει:**
Dimension


---

### getIncludeHiddenSlides {#getIncludeHiddenSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| getIncludeHiddenSlides () | Get or sets if hidden slides should be included. |

 **Επιστρέφει:**
boolean


---

### run {#run}

| Όνομα | Περιγραφή |
| --- | --- |
| run (com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides. ISlide>) | Run the animation events generation for each slide. |

 **Επιστρέφει:**
void


---

### run {#run}

| Όνομα | Περιγραφή |
| --- | --- |
| run (com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides. ISlide>, int, [PresentationPlayer.FrameTick](../presentationplayer.frametick)) | Run the animation events generation for each slide. |

 **Επιστρέφει:**
void


---

### setDefaultDelay {#setDefaultDelay}

| Όνομα | Περιγραφή |
| --- | --- |
| setDefaultDelay (int) | Gets or sets default delay time [ms]. |

 **Επιστρέφει:**
void


---

### setIncludeHiddenSlides {#setIncludeHiddenSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| setIncludeHiddenSlides (boolean) | Get or sets if hidden slides should be included. |

 **Επιστρέφει:**
void


---

### setNewAnimation {#setNewAnimation}

| Όνομα | Περιγραφή |
| --- | --- |
| setNewAnimation ([PresentationAnimationsGenerator.NewAnimation](../presentationanimationsgenerator.newanimation)) | Set a new animation event. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| anim | [PresentationAnimationsGenerator.NewAnimation](../presentationanimationsgenerator.newanimation) | Animation event. |

 **Επιστρέφει:**
void


---