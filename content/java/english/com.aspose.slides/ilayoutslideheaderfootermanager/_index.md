---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Java API Reference
description: Represents manager which holds behavior of the layout slide footer date-time page number placeholders and all child placeholders.
type: docs
url: /com.aspose.slides/ilayoutslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Represents manager which holds behavior of the layout slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.
## Methods

| Method | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes layout slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes layout slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes layout slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to layout slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to layout slide date-time placeholder and all child date-time placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Changes layout slide footer placeholder and all child footer placeholders visibility. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on master slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a footer placeholders visible, otherwise - hides them. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Changes layout slide page number placeholder and all child page number placeholders visibility. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a page number placeholders visible, otherwise - hides them. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Changes layout slide date-time placeholder and all child date-time placeholders visibility. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - makes a date-time placeholders visible, otherwise - hides them. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Sets text to layout slide footer placeholder and all child footer placeholders. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to set. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Sets text to layout slide date-time placeholder and all child date-time placeholders. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to set. |

