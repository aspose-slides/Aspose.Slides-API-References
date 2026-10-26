---
title: ForEach_
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/foreach_/
---
## ForEach_ κλάση

Represents a group of methods intended to iterate over different Presentation model objects. These methods can be useful if you need to iterate and change some Presentation' elements formatting or content, e.g. change each portion formatting.

### ForEach_ {#ForEach_}

| Name | Description |
| --- | --- |
| ForEach_() |  |

**Επιστρέφει:**
ForEach_


---


### layoutSlide {#layoutSlide}

| Name | Description |
| --- | --- |
| layoutSlide ([Presentation](../presentation), [ForEach_.ForEachLayoutSlideCallback](../foreach_.foreachlayoutslidecallback)) | Επανάληψη σε κάθε #layoutSlide(Presentation,ForEachLayoutSlideCallback) στο Presentation. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation για επανάληψη διατάξεων διαφανειών |
| forEachLayoutSlide | [ForEach_.ForEachLayoutSlideCallback](../foreach_.foreachlayoutslidecallback) | Callback που θα κληθεί για κάθε διάταξη διαφάνειας |

**Επιστρέφει:**
void


---


### masterSlide {#masterSlide}

| Name | Description |
| --- | --- |
| masterSlide ([Presentation](../presentation), [ForEach_.ForEachMasterSlideCallback](../foreach_.foreachmasterslidecallback)) | Επανάληψη σε κάθε #masterSlide(Presentation,ForEachMasterSlideCallback) στο Presentation. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation για επανάληψη κύριων διαφανειών |
| forEachMasterSlide | [ForEach_.ForEachMasterSlideCallback](../foreach_.foreachmasterslidecallback) | Callback που θα κληθεί για κάθε κύρια διαφάνεια |

**Επιστρέφει:**
void


---


### paragraph {#paragraph}

| Name | Description |
| --- | --- |
| paragraph ([Presentation](../presentation), [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback)) | Επανάληψη σε κάθε Paragraph στο Presentation. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation για επανάληψη παραγράφων |
| forEachParagraph | [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback) | Callback που θα κληθεί για κάθε παράγραφο. Τα σχήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) και #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

**Επιστρέφει:**
void


---


### paragraph {#paragraph}

| Name | Description |
| --- | --- |
| paragraph ([Presentation](../presentation), boolean, [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback)) | Επανάληψη σε κάθε Paragraph στο Presentation. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation για επανάληψη παραγράφων |
| includeNotes | boolean | Σημαία που υποδεικνύει εάν θα συμπεριληφθούν οι NotesSlides στην επεξεργασία. |
| forEachParagraph | [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback) | Callback που θα κληθεί για κάθε παράγραφο. Τα σχήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) και NotesSlide |

**Επιστρέφει:**
void


---


### portion {#portion}

| Name | Description |
| --- | --- |
| portion ([Presentation](../presentation), [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback)) | Επανάληψη σε κάθε Portion στο Presentation. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation για επανάληψη τμημάτων |
| forEachPortion | [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback) | Callback που θα κληθεί για κάθε τμήμα. Τα τμήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) και #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

**Επιστρέφει:**
void


---


### portion {#portion}

| Name | Description |
| --- | --- |
| portion ([Presentation](../presentation), boolean, [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback)) | Επανάληψη σε κάθε Portion στο Presentation. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation για επανάληψη τμημάτων |
| includeNotes | boolean | Σημαία που υποδεικνύει εάν θα συμπεριληφθούν οι NotesSlides στην επεξεργασία. |
| forEachPortion | [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback) | Callback που θα κληθεί για κάθε τμήμα. Τα τμήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) και NotesSlide |

**Επιστρέφει:**
void


---


### shape {#shape}

| Name | Description |
| --- | --- |
| shape ([Presentation](../presentation), [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Επανάληψη σε κάθε Shape στο Presentation. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation για επανάληψη σχήματος διάταξης |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | Callback που θα κληθεί για κάθε σχήμα. Τα σχήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) και #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

**Επιστρέφει:**
void


---


### shape {#shape}

| Name | Description |
| --- | --- |
| shape ([Presentation](../presentation), boolean, [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Επανάληψη σε κάθε Shape στο Presentation. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation για επανάληψη σχήματος διάταξης |
| includeNotes | boolean | Σημαία που υποδεικνύει εάν θα συμπεριληφθούν οι NotesSlides στην επεξεργασία. |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | Callback που θα κληθεί για κάθε σχήμα. Τα σχήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) και NotesSlide εάν χρειαστεί. |

**Επιστρέφει:**
void


---


### shape {#shape}

| Name | Description |
| --- | --- |
| shape ([BaseSlide](../baseslide), [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Επανάληψη σε κάθε Shape στο BaseSlide. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| baseSlide | [BaseSlide](../baseslide) | Slide για επανάληψη σχήματος διάταξης |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | Callback που θα κληθεί για κάθε σχήμα. Το BaseSlide είναι η βασική μορφή για #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) και #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

**Επιστρέφει:**
void


---


### slide {#slide}

| Name | Description |
| --- | --- |
| slide ([Presentation](../presentation), [ForEach_.ForEachSlideCallback](../foreach_.foreachslidecallback)) | Επανάληψη σε κάθε #slide(Presentation,ForEachSlideCallback) στο Presentation. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation για επανάληψη διαφανειών |
| forEachSlide | [ForEach_.ForEachSlideCallback](../foreach_.foreachslidecallback) | Callback που θα κληθεί για κάθε διαφάνεια |

**Επιστρέφει:**
void


---