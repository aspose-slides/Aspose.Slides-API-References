---
title: BaseSlide
second_title: Aspose.Slides for Java API Reference
description: Represents common data for all slide types.
type: docs
weight: 44
url: /java/com.aspose.slides/baseslide/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Represents common data for all slide types.
## Methods

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Returns the shapes of a slide. |
| [getControls()](#getControls--) | Returns the collection of ActiveX controls on a slide. |
| [getName()](#getName--) | Returns or sets the name of a slide. |
| [setName(String value)](#setName-java.lang.String-) | Returns or sets the name of a slide. |
| [getSlideId()](#getSlideId--) | Returns the ID of a slide. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Determines whether the two IBaseSlide instances are equal. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [createThemeEffective()](#createThemeEffective--) | Returns an effective theme for this slide. |
| [getCustomData()](#getCustomData--) | Returns the slide's custom data. |
| [getTimeline()](#getTimeline--) | Returns animation timeline object. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Returns the Transition object which contains information about how the specified slide advances during a slide show. |
| [getBackground()](#getBackground--) | Returns slide's background. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Provides easy access to contained hyperlinks. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifies if shapes on the master slide should be shown on slides or not. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifies if shapes on the master slide should be shown on slides or not. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Finds first occurrence of a shape with the specified alternative text. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Returns IPresentation interface. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Returns the shapes of a slide. Read-only [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Returns:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```


Returns the collection of ActiveX controls on a slide. Read-only [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Returns:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```


Returns or sets the name of a slide. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Returns or sets the name of a slide. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```


Returns the ID of a slide. Read-only long.

**Returns:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```


Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The IBaseSlide to compare with the current IBaseSlide. |

**Returns:**
boolean -  **true**  if the specified IBaseSlide is equal to the current IBaseSlide; otherwise,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


Joins runs with same formatting in all paragraphs all acceptable shapes.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```


Joins runs with same formatting in all paragraphs in all acceptable shapes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Returns an effective theme for this slide.

**Returns:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Returns the slide's custom data. Read-only [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```


Returns animation timeline object. Read-only [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Returns:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```


Returns the Transition object which contains information about how the specified slide advances during a slide show. Read-only [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Returns:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```


Returns slide's background. Read-only [IBackground](../../com.aspose.slides/ibackground).

**Returns:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Provides easy access to contained hyperlinks. Read-only [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean.

**Returns:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```


Finds first occurrence of a shape with the specified alternative text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| altText | java.lang.String | Alternative text. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Shape object or null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns IPresentation interface. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the base slide. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
