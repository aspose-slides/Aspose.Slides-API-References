---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of all layout slides in presentation.
type: docs
weight: 806
url: /java/com.aspose.slides/igloballayoutslidecollection/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Represents a collection of all layout slides in presentation. Extends ILayoutSlideCollection interface with methods for adding/cloning layout slides in context of uniting of the individual collections of master's layout slides.
## Methods

| Method | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified layout slide to the presentation. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Adds a copy of a specified layout slide to the presentation. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Adds a new layout slide to the presentation. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Adds a copy of a specified layout slide to the presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide to clone.

--------------------

When cloning a layout between different presentations layout's master can be cloned too to keep source formatting. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Added slide.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Adds a copy of a specified layout slide to the presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide to clone. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide for a new layout.

--------------------

New layout will be linked with defined master in destination presentation. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Added slide.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Adds a new layout slide to the presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide for a new layout. |
| layoutType | byte | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example "Title Slide" or "1\_Title Slide", "2\_..", etc.).

--------------------

1) Added layout for value SlideLayoutType.Custom of layoutType contains no placeholders and no shapes. 2) Analogue of this method is method [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) accessed with ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) property. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Added slide.
