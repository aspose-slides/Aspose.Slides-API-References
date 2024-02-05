---
title: MasterNotesSlide
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/masternotesslide/
---

## MasterNotesSlide class

 Represents master slide for notes.
 
### createThemeEffective {#createThemeEffective}

| Name | Description |
| --- | --- |
| createThemeEffective() | Returns an effective theme for this slide. |

 **Result:**
ThemeEffectiveData


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals([Slide](../slide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [Slide](../slide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals([MasterNotesSlide](../masternotesslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [MasterNotesSlide](../masternotesslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals([MasterSlide](../masterslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [MasterSlide](../masterslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals([LayoutSlide](../layoutslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [LayoutSlide](../layoutslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals([MasterHandoutSlide](../masterhandoutslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [MasterHandoutSlide](../masterhandoutslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals([NotesSlide](../notesslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [NotesSlide](../notesslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### findShapeByAltText {#findShapeByAltText}

| Name | Description |
| --- | --- |
| findShapeByAltText(String) | Finds first occurrence of a shape with the specified alternative text. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| altText | String | Alternative text. |

 **Result:**
[SummaryZoomSection](../summaryzoomsection), [AutoShape](../autoshape), [AudioFrame](../audioframe), [OleObjectFrame](../oleobjectframe), [SummaryZoomFrame](../summaryzoomframe), [ZoomFrame](../zoomframe), [GraphicalObject](../graphicalobject), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [GeometryShape](../geometryshape), [SmartArtShape](../smartartshape), [SmartArt](../smartart), [Ink](../ink), [Chart](../chart), [GroupShape](../groupshape), [Table](../table), [SectionZoomFrame](../sectionzoomframe), [Shape](../shape), [LegacyDiagram](../legacydiagram), [Connector](../connector)


---


### getBackground {#getBackground}

| Name | Description |
| --- | --- |
| getBackground() | Returns slide's background. Read-only IBackground. |

 **Result:**
[Background](../background)


---


### getControls {#getControls}

| Name | Description |
| --- | --- |
| getControls() | Returns the collection of ActiveX controls on a slide. Read-only IControlCollection. |

 **Result:**
[ControlCollection](../controlcollection)


---


### getCustomData {#getCustomData}

| Name | Description |
| --- | --- |
| getCustomData() | Returns the slide's custom data. Read-only ICustomData. |

 **Result:**
[CustomData](../customdata)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| Name | Description |
| --- | --- |
| getHeaderFooterManager() | Returns HeaderFooter manager of the master notes slide. Read-only IMasterHandoutSlideHeaderFooterManager. |

 **Result:**
[MasterNotesSlideHeaderFooterManager](../masternotesslideheaderfootermanager)


---


### getHyperlinkQueries {#getHyperlinkQueries}

| Name | Description |
| --- | --- |
| getHyperlinkQueries() | Provides easy access to contained hyperlinks. Read-only IHyperlinkQueries. |

 **Result:**
[HyperlinkQueries](../hyperlinkqueries)


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName() | Returns or sets the name of a slide. Read/write String. |

 **Result:**
String


---


### getNotesStyle {#getNotesStyle}

| Name | Description |
| --- | --- |
| getNotesStyle() | Returns the style of a notes text. Read-only ITextStyle. |

 **Result:**
[TextStyle](../textstyle)


---


### getParent_Immediate {#getParent_Immediate}

| Name | Description |
| --- | --- |
| getParent_Immediate() |  |


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation() | Returns IPresentation interface. Read-only IPresentation. |

 **Result:**
[Presentation](../presentation)


---


### getShapes {#getShapes}

| Name | Description |
| --- | --- |
| getShapes() | Returns the shapes of a slide. Read-only IShapeCollection. |

 **Result:**
[ShapeCollection](../shapecollection)


---


### getShowMasterShapes {#getShowMasterShapes}

| Name | Description |
| --- | --- |
| getShowMasterShapes() | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

 **Result:**
boolean

 **Error**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.NotSupportedException | Thrown if set true for master slide. |


---


### getShowMasterShapes {#getShowMasterShapes}

| Name | Description |
| --- | --- |
| getShowMasterShapes() | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

 **Result:**
boolean

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | Thrown if set true for master slide. |


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide() |  |

 **Result:**
[Slide](../slide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [MasterSlide](../masterslide), [LayoutSlide](../layoutslide), [MasterHandoutSlide](../masterhandoutslide), [NotesSlide](../notesslide)


---


### getSlideId {#getSlideId}

| Name | Description |
| --- | --- |
| getSlideId() | Returns the ID of a slide. Read-only long. |

 **Result:**
long


---


### getSlideShowTransition {#getSlideShowTransition}

| Name | Description |
| --- | --- |
| getSlideShowTransition() | Returns the Transition object which contains information about how the specified slide advances during a slide show. Read-only ISlideShowTransition. |

 **Result:**
[SlideShowTransition](../slideshowtransition)


---


### getThemeManager {#getThemeManager}

| Name | Description |
| --- | --- |
| getThemeManager() | Returns the theme manager. Read-only IMasterThemeManager. |

 **Result:**
[MasterThemeManager](../masterthememanager)


---


### getTimeline {#getTimeline}

| Name | Description |
| --- | --- |
| getTimeline() | Returns animation timeline object. Read-only IAnimationTimeLine. |

 **Result:**
[AnimationTimeLine](../animationtimeline)


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting() | Joins runs with same formatting in all paragraphs all acceptable shapes. |


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting([ShapeCollection](../shapecollection)) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |


---


### setName {#setName}

| Name | Description |
| --- | --- |
| setName(String) | Returns or sets the name of a slide. Read/write String. |


---


### setShowMasterShapes {#setShowMasterShapes}

| Name | Description |
| --- | --- |
| setShowMasterShapes(boolean) | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

 **Error**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.NotSupportedException | Thrown if set true for master slide. |


---


### setShowMasterShapes {#setShowMasterShapes}

| Name | Description |
| --- | --- |
| setShowMasterShapes(boolean) | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | Thrown if set true for master slide. |


---


