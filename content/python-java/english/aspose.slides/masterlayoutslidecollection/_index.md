---
title: MasterLayoutSlideCollection
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/masterlayoutslidecollection/
---

## MasterLayoutSlideCollection class

 Represents a collections of all layout slides of defined master slide.
 Extends LayoutSlideCollection class with methods for adding/inserting/removing/cloning/reordering 
 layout slides in context of the individual collections of master's layout slides.
 
### add {#add}

| Name | Description |
| --- | --- |
| add(byte, String) | Adds a new layout slide to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| layoutType | byte | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example "Title Slide" or "1_Title Slide", "2_..", etc.). 1) Added layout for value SlideLayoutType.Custom of layoutType contains no placeholders and no shapes. 2) Analogue of this method is method IGlobalLayoutSlideCollection#add(IMasterSlide,byte,String) accessed with ( IPresentation#getLayoutSlides) property. |

 **Result:**
[LayoutSlide](../layoutslide)

 **Error**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Thrown if layout name value layoutName is already in use in this collection of the layouts. |


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone([LayoutSlide](../layoutslide)) | Adds a copy of a specified layout slide to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceLayout | [LayoutSlide](../layoutslide) | Slide to clone. 1) New layout will be linked with parent master slide for this layout slides collection. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint. 2) Analogue of this method is method IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) accessed with ( IPresentation#getLayoutSlides) property. |

 **Result:**
[LayoutSlide](../layoutslide)


---


### copyTo {#copyTo}

| Name | Description |
| --- | --- |
| copyTo(Array, int) | Copies all elements from the collection to the specified array. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| array | Array | Target array. |
| index | int | Starting index in the target array. |


---


### getByType {#getByType}

| Name | Description |
| --- | --- |
| getByType(byte) | Returns the first layout slide of specified type. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | byte | A type of layout slide to find. |

 **Result:**
[LayoutSlide](../layoutslide)


---


### getParent_Immediate {#getParent_Immediate}

| Name | Description |
| --- | --- |
| getParent_Immediate() |  |


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot() | Returns a synchronization root. Read-only Object. |

 **Result:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item(int) | Returns the layout slide by index. Read-only LayoutSlide. |

 **Result:**
[LayoutSlide](../layoutslide)


---


### insert {#insert}

| Name | Description |
| --- | --- |
| insert(int, byte, String) | Inserts a new layout slide to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| layoutType | byte | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example "Title Slide" or "1_Title Slide", "2_..", etc.). Inserted layout for value SlideLayoutType.Custom of layoutType contains no placeholders and no shapes. |

 **Result:**
[LayoutSlide](../layoutslide)

 **Error**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Thrown if layout name value layoutName is already in use in this collection of the layouts. |


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone(int, [LayoutSlide](../layoutslide)) | Inserts a copy of a specified layout slide to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceLayout | [LayoutSlide](../layoutslide) | Slide to clone. New layout will be linked with parent master slide for this layout slides collection. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint. |

 **Result:**
[LayoutSlide](../layoutslide)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Result:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator() | Returns an enumerator that iterates through the collection. |

 **Result:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava() | Returns a java iterator for the entire collection. |

 **Result:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove([LayoutSlide](../layoutslide)) | Removes a layout from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | [LayoutSlide](../layoutslide) | The layout slide to remove from the collection. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove method to simplify code. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is used in presentation (its HasDependingSlides property is true). |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt(int) | Removes the element at the specified index of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove method to simplify code. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is used in presentation (its HasDependingSlides property is true). |


---


### removeUnused {#removeUnused}

| Name | Description |
| --- | --- |
| removeUnused() | Removes unused layout slides (layout slides whose HasDependingSlides is false). |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder(int, [LayoutSlide](../layoutslide)) | Moves layout slide from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| layoutSlide | [LayoutSlide](../layoutslide) | Slide to move. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size() | Returns the number of layout slides in a collection. Read-only int. |

 **Result:**
int


---


