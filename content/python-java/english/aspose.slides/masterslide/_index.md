---
title: MasterSlide
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/masterslide/
---

## MasterSlide class

 Represents a master slide in a presentation.
 
### applyExternalThemeToDependingSlides {#applyExternalThemeToDependingSlides}

| Name | Description |
| --- | --- |
| applyExternalThemeToDependingSlides(String) | Creates a new master slide based on the current one, applying an external theme to it and applies the created master slide to all dependent slides. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the external theme file (.thmx). |

 **Result:**
[MasterSlide](../masterslide)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxReadException | When external theme cannot be applied. |


---


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
| equals([NotesSlide](../notesslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [NotesSlide](../notesslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


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
| equals([MasterSlide](../masterslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [MasterSlide](../masterslide) | The IBaseSlide to compare with the current IBaseSlide. |

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
[Chart](../chart), [PictureFrame](../pictureframe), [Table](../table), [SmartArt](../smartart), [AudioFrame](../audioframe), [Connector](../connector), [SectionZoomFrame](../sectionzoomframe), [SmartArtShape](../smartartshape), [ZoomFrame](../zoomframe), [GeometryShape](../geometryshape), [ZoomObject](../zoomobject), [GraphicalObject](../graphicalobject), [Ink](../ink), [LegacyDiagram](../legacydiagram), [SummaryZoomFrame](../summaryzoomframe), [SummaryZoomSection](../summaryzoomsection), [GroupShape](../groupshape), [VideoFrame](../videoframe), [OleObjectFrame](../oleobjectframe), [AutoShape](../autoshape), [Shape](../shape)


---


### getBackground {#getBackground}

| Name | Description |
| --- | --- |
| getBackground() | Returns slide's background. Read-only IBackground. |

 **Result:**
[Background](../background)


---


### getBodyStyle {#getBodyStyle}

| Name | Description |
| --- | --- |
| getBodyStyle() | Returns the style of a body text. Read-only ITextStyle. |

 **Result:**
[TextStyle](../textstyle)


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


### getDependingSlides {#getDependingSlides}

| Name | Description |
| --- | --- |
| getDependingSlides() | Returns an array with all slides, which depend on this master slide. |

 **Result:**
[Slide](../slide)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| Name | Description |
| --- | --- |
| getHeaderFooterManager() | Returns HeaderFooter manager of the master slide. Read-only IMasterSlideHeaderFooterManager. |

 **Result:**
[MasterSlideHeaderFooterManager](../masterslideheaderfootermanager)


---


### getHyperlinkQueries {#getHyperlinkQueries}

| Name | Description |
| --- | --- |
| getHyperlinkQueries() | Provides easy access to contained hyperlinks. Read-only IHyperlinkQueries. |

 **Result:**
[HyperlinkQueries](../hyperlinkqueries)


---


### getLayoutSlides {#getLayoutSlides}

| Name | Description |
| --- | --- |
| getLayoutSlides() | Returns the collection of child layout slides for this master slide. Read-only IMasterLayoutSlideCollection. You can access to alternative API for adding/inserting/removing/cloning layout slides by using ( IPresentation#getLayoutSlides) property. |

 **Result:**
[MasterLayoutSlideCollection](../masterlayoutslidecollection)


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName() | Returns or sets the name of a master slide. Read/write String. |

 **Result:**
String


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName() | Returns or sets the name of a slide. Read/write String. |

 **Result:**
String


---


### getOtherStyle {#getOtherStyle}

| Name | Description |
| --- | --- |
| getOtherStyle() | Returns the style of an other text. Read-only ITextStyle. |

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


### getPreserve {#getPreserve}

| Name | Description |
| --- | --- |
| getPreserve() | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call MasterSlideCollection#removeUnused(boolean) Read/write boolean. |

 **Result:**
boolean


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
 | NotSupportedException | Thrown if set {@code true} for master slide. |


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
[MasterNotesSlide](../masternotesslide), [LayoutSlide](../layoutslide), [BaseSlide](../baseslide), [NotesSlide](../notesslide), [Slide](../slide), [MasterHandoutSlide](../masterhandoutslide), [MasterSlide](../masterslide)


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


### getTitleStyle {#getTitleStyle}

| Name | Description |
| --- | --- |
| getTitleStyle() | Returns the style of a title text. Read-only ITextStyle. |

 **Result:**
[TextStyle](../textstyle)


---


### hasDependingSlides {#hasDependingSlides}

| Name | Description |
| --- | --- |
| hasDependingSlides() | Returns true if there exists at least one slide that depends on this master slide. Read-only boolean. |

 **Result:**
boolean


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
| setName(String) | Returns or sets the name of a master slide. Read/write String. |


---


### setName {#setName}

| Name | Description |
| --- | --- |
| setName(String) | Returns or sets the name of a slide. Read/write String. |


---


### setPreserve {#setPreserve}

| Name | Description |
| --- | --- |
| setPreserve(boolean) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call MasterSlideCollection#removeUnused(boolean) Read/write boolean. |


---


### setShowMasterShapes {#setShowMasterShapes}

| Name | Description |
| --- | --- |
| setShowMasterShapes(boolean) | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | Thrown if set {@code true} for master slide. |


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


