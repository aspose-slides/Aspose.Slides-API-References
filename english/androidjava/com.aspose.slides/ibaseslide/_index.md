---
title: IBaseSlide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents common data for all slide types.
type: docs
weight: 660
url: /androidjava/com.aspose.slides/ibaseslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
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
| [getCustomData()](#getCustomData--) | Returns the slide's custom data. |
| [getTimeline()](#getTimeline--) | Returns animation timeline object. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Returns the TransitionEx object which contains information about how the specified slide advances during a slide show. |
| [getBackground()](#getBackground--) | Returns slide's background. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Provides easy access to contained hyperlinks. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifies if shapes on the master slide should be shown on slides or not. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifies if shapes on the master slide should be shown on slides or not. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Finds first occurrence of a shape with the specified alternative text. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Determines whether the two IBaseSlide instances are equal. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


Returns the shapes of a slide. Read-only [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Returns:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


Returns the collection of ActiveX controls on a slide. Read-only [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Returns:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


Returns or sets the name of a slide. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Returns or sets the name of a slide. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


Returns the ID of a slide. Read-only long.

**Returns:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


Returns the slide's custom data. Read-only [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


Returns animation timeline object. Read-only [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Returns:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


Returns the TransitionEx object which contains information about how the specified slide advances during a slide show. Read-only [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Returns:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


Returns slide's background. Read-only [IBackground](../../com.aspose.slides/ibackground).

**Returns:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
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
public abstract IShape findShapeByAltText(String altText)
```


Finds first occurrence of a shape with the specified alternative text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| altText | java.lang.String | Alternative text. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object or null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Joins runs with same formatting in all paragraphs in all acceptable shapes.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The IBaseSlide to compare with the current IBaseSlide. |

**Returns:**
boolean - **true** if the specified IBaseSlide is equal to the current IBaseSlide; otherwise, **false**.
