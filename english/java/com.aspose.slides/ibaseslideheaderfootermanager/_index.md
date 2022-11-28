---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides for Java API Reference
description: Represents manager which holds behavior of the footer date-time page number placeholders for all slide types.
type: docs
weight: 661
url: /java/com.aspose.slides/ibaseslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Represents manager which holds behavior of the footer, date-time, page number placeholders for all slide types.
## Methods

| Method | Description |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Gets value indicating that a footer placeholder is present. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Gets value indicating that a page number placeholder is present. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Gets value indicating that a date-time placeholder is present. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Changes slide footer placeholder visibility. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Changes slide page number placeholder visibility. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Changes slide date-time placeholder visibility. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Sets text to slide footer placeholder. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Sets text to slide date-time placeholder. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


Gets value indicating that a footer placeholder is present. Read boolean.

**Returns:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


Gets value indicating that a page number placeholder is present. Read boolean.

**Returns:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


Gets value indicating that a date-time placeholder is present. Read boolean.

**Returns:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


Changes slide footer placeholder visibility.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a footer placeholder visible, otherwise - hides it. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


Changes slide page number placeholder visibility.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a page number placeholder visible, otherwise - hides it. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


Changes slide date-time placeholder visibility.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a date-time placeholder visible, otherwise - hides it. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


Sets text to slide footer placeholder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to set. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


Sets text to slide date-time placeholder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to set. |

