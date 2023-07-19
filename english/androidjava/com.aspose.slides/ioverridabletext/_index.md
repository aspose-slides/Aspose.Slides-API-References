---
title: IOverridableText
second_title: Aspose.Slides for Android via Java API Reference
description: Represents overridable text for a chart.
type: docs
weight: 955
url: /androidjava/com.aspose.slides/ioverridabletext/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Represents overridable text for a chart.
## Methods

| Method | Description |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Can contain a rich formatted text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialize TextFrameForOverriding with the text in paramener "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text. Auto-generated text is an implicit property of the data label, the display unit label of the value axis, the axis title, the chart title, the label of the trendline. Auto-generated text is formatted with the IFormattedTextContainer.TextFormat property. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text for a new TextFrameForOverriding. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe) - Text frame [ITextFrame](../../com.aspose.slides/itextframe)
