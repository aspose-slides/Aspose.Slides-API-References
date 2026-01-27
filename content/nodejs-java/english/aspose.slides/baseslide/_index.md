---
title: BaseSlide
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/baseslide/
---

## BaseSlide class

  Represents common data for all slide types.
 
### createThemeEffective {#createThemeEffective}

| Name | Description |
| --- | --- |
| createThemeEffective () | Returns an effective theme for this slide. |

 **Returns:**
ThemeEffectiveData


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([MasterHandoutSlide](../masterhandoutslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [MasterHandoutSlide](../masterhandoutslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Returns:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([BaseSlide](../baseslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [BaseSlide](../baseslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Returns:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([Slide](../slide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [Slide](../slide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Returns:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([LayoutSlide](../layoutslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [LayoutSlide](../layoutslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Returns:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([MasterSlide](../masterslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [MasterSlide](../masterslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Returns:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([NotesSlide](../notesslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [NotesSlide](../notesslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Returns:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([MasterNotesSlide](../masternotesslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [MasterNotesSlide](../masternotesslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Returns:**
boolean


---


### findShapeByAltText {#findShapeByAltText}

| Name | Description |
| --- | --- |
| findShapeByAltText (String) | Finds first occurrence of a shape with the specified alternative text. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| altText | String | Alternative text. |

 **Returns:**
[SummaryZoomFrame](../summaryzoomframe), [InkActions](../inkactions), [LegacyDiagram](../legacydiagram), [Shape](../shape), [Ink](../ink), [ZoomObject](../zoomobject), [SmartArt](../smartart), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [Connector](../connector), [GraphicalObject](../graphicalobject), [VideoFrame](../videoframe), [PictureFrame](../pictureframe), [GroupShape](../groupshape), [AudioFrame](../audioframe), [SectionZoomFrame](../sectionzoomframe), [OleObjectFrame](../oleobjectframe), [SmartArtShape](../smartartshape), [AutoShape](../autoshape), [Chart](../chart), [GeometryShape](../geometryshape), [Table](../table)


---


### getBackground {#getBackground}

| Name | Description |
| --- | --- |
| getBackground () | Returns slide's background. Read-only IBackground. |

 **Returns:**
[Background](../background)


---


### getControls {#getControls}

| Name | Description |
| --- | --- |
| getControls () | Returns the collection of ActiveX controls on a slide. Read-only IControlCollection. |

 **Returns:**
[ControlCollection](../controlcollection)


---


### getCustomData {#getCustomData}

| Name | Description |
| --- | --- |
| getCustomData () | Returns the slide's custom data. Read-only ICustomData. |

 **Returns:**
[CustomData](../customdata)


---


### getHyperlinkQueries {#getHyperlinkQueries}

| Name | Description |
| --- | --- |
| getHyperlinkQueries () | Provides easy access to contained hyperlinks. Read-only IHyperlinkQueries. |

 **Returns:**
[HyperlinkQueries](../hyperlinkqueries)


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName () | Returns or sets the name of a slide. Read/write String. |

 **Returns:**
String


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns IPresentation interface. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getShapes {#getShapes}

| Name | Description |
| --- | --- |
| getShapes () | Returns the shapes of a slide. Read-only IShapeCollection. |

 **Returns:**
[ShapeCollection](../shapecollection)


---


### getShowMasterShapes {#getShowMasterShapes}

| Name | Description |
| --- | --- |
| getShowMasterShapes () | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

 **Returns:**
boolean

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | Thrown if set true for master slide. |


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () |  |

 **Returns:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [Slide](../slide), [LayoutSlide](../layoutslide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSlideId {#getSlideId}

| Name | Description |
| --- | --- |
| getSlideId () | Returns the ID of a slide. Read-only long. |

 **Returns:**
long


---


### getSlideShowTransition {#getSlideShowTransition}

| Name | Description |
| --- | --- |
| getSlideShowTransition () | Returns the Transition object which contains information about how the specified slide advances during a slide show. Read-only ISlideShowTransition. |

 **Returns:**
[SlideShowTransition](../slideshowtransition)


---


### getTimeline {#getTimeline}

| Name | Description |
| --- | --- |
| getTimeline () | Returns animation timeline object. Read-only IAnimationTimeLine. |

 **Returns:**
[AnimationTimeLine](../animationtimeline)


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Joins runs with same formatting in all paragraphs all acceptable shapes. |


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting ([ShapeCollection](../shapecollection)) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |


---


### setName {#setName}

| Name | Description |
| --- | --- |
| setName (String) | Returns or sets the name of a slide. Read/write String. |


---


### setShowMasterShapes {#setShowMasterShapes}

| Name | Description |
| --- | --- |
| setShowMasterShapes (boolean) | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | Thrown if set true for master slide. |


---


