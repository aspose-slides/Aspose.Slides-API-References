---
title: IPresentationHeaderFooterManager
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents manager which holds behavior of all footer date-time and page number placeholders of presentation.
type: docs
weight: 978
url: /java/com.aspose.slides/ipresentationheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Represents manager which holds behavior of all footer, date-time and page number placeholders of presentation.
## Methods

| Method | Description |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Changes all header placeholders visibility, including notes master, notes slides and handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Changes all footer placeholders visibility, including master slides, layout slides and slides. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Changes all page number placeholders visibility, including master slides, layout slides and slides. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Changes all date-time placeholders visibility, including master slides, layout slides and slides. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Sets text to all header placeholders, including notes master, notes slides and handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Sets text to all footer placeholders, including master slides, layout slides and slides. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Sets text to all date-time placeholders, including master slides, layout slides and slides. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Changes the footer, date-time and page number placeholders visibility for all title slides and for first layout slide. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```


Changes all header placeholders visibility, including notes master, notes slides and handout master.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a header placeholders visible, otherwise - hides them. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```


Changes all footer placeholders visibility, including master slides, layout slides and slides.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a footer placeholders visible, otherwise - hides them. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```


Changes all page number placeholders visibility, including master slides, layout slides and slides.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a page number placeholders visible, otherwise - hides them. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```


Changes all date-time placeholders visibility, including master slides, layout slides and slides.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a date-time placeholders visible, otherwise - hides them. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```


Sets text to all header placeholders, including notes master, notes slides and handout master.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to set. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```


Sets text to all footer placeholders, including master slides, layout slides and slides.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to set. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```


Sets text to all date-time placeholders, including master slides, layout slides and slides.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to set. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```


Changes the footer, date-time and page number placeholders visibility for all title slides and for first layout slide. Title slides \\u2013 slides based on first layout slide (regardless of type of this first layout).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a placeholders visible, otherwise - hides them. |

