---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collections of all layout slides of defined master slide.
type: docs
url: /com.aspose.slides/imasterlayoutslidecollection/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Represents a collections of all layout slides of defined master slide. Extends ILayoutSlideCollection interface with methods for adding/inserting/removing/cloning layout slides in context of the individual collections of master's layout slides.
## Methods

| Method | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified layout slide to the end of the collection. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Inserts a copy of a specified layout slide to specified position of the collection. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Adds a new layout slide to the end of the collection. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Inserts a new layout slide to specified position of the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Moves layout slide from the collection to the specified position. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Adds a copy of a specified layout slide to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide to clone.

--------------------

1) New layout will be linked with parent master slide for this layout slides collection. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint. 2) Analogue of this method is method [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) accessed with [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) property. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Added slide.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```


Inserts a copy of a specified layout slide to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide to clone.

--------------------

New layout will be linked with parent master slide for this layout slides collection. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Inserted slide.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```


Adds a new layout slide to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layoutType | byte | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example "Title Slide" or "1\_Title Slide", "2\_..", etc.).

--------------------

1) Added layout for value SlideLayoutType.Custom of layoutType contains no placeholders and no shapes. 2) Analogue of this method is method [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) accessed with [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) property. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Added slide.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```


Inserts a new layout slide to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| layoutType | byte | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example "Title Slide" or "1\_Title Slide", "2\_..", etc.).

--------------------

Inserted layout for value SlideLayoutType.Custom of layoutType contains no placeholders and no shapes. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Inserted slide.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove.

--------------------

1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) method to simplify code. |

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```


Moves layout slide from the collection to the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide to move. |

