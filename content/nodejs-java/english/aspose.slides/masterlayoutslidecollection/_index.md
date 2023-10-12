---
title: MasterLayoutSlideCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/masterlayoutslidecollection/
---

## MasterLayoutSlideCollection class

 Represents a collections of all layout slides of defined master slide.
 Extends LayoutSlideCollection class with methods for adding/inserting/removing/cloning/reordering 
 layout slides in context of the individual collections of master's layout slides.
 
| [add] ([byte], [String]) | Adds a new layout slide to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| layoutType | [byte] | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [String] | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example "Title Slide" or "1_Title Slide", "2_..", etc.). 1) Added layout for value SlideLayoutType.Custom of layoutType contains no placeholders and no shapes. 2) Analogue of this function is function IGlobalLayoutSlideCollection#add(IMasterSlide,byte,String) accessed with ( IPresentation#getLayoutSlides) property. |

### Result
[LayoutSlide]

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Thrown if layout name value layoutName is already in use in this collection of the layouts. |


---


| [addClone] ([LayoutSlide]) | Adds a copy of a specified layout slide to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceLayout | [LayoutSlide] | Slide to clone. 1) New layout will be linked with parent master slide for this layout slides collection. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint. 2) Analogue of this function is function IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) accessed with ( IPresentation#getLayoutSlides) property. |

### Result
[LayoutSlide]


---


| [insert] ([int], [byte], [String]) | Inserts a new layout slide to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new slide. |
| layoutType | [byte] | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [String] | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example "Title Slide" or "1_Title Slide", "2_..", etc.). Inserted layout for value SlideLayoutType.Custom of layoutType contains no placeholders and no shapes. |

### Result
[LayoutSlide]

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Thrown if layout name value layoutName is already in use in this collection of the layouts. |


---


| [insertClone] ([int], [LayoutSlide]) | Inserts a copy of a specified layout slide to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new slide. |
| sourceLayout | [LayoutSlide] | Slide to clone. New layout will be linked with parent master slide for this layout slides collection. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint. |

### Result
[LayoutSlide]


---


| [removeAt] ([int]) | Removes the element at the specified index of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index of the element to remove. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove function to simplify code. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is used in presentation (its HasDependingSlides property is true). |


---


| [reorder] ([int], [LayoutSlide]) | Moves layout slide from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| layoutSlide | [LayoutSlide] | Slide to move. |


---


