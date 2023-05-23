---
title: TextStyle
second_title: Aspose.Slides for Java API Reference
description: This class contains the text style formatting properties.
type: docs
weight: 568
url: /java/com.aspose.slides/textstyle/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

This class contains the text style formatting properties.
## Fields

| Field | Description |
| --- | --- |
| [MaxLevelCount](#MaxLevelCount) | Maximum count of style levels that can be defined. |
## Methods

| Method | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | If level of style exist returns it, otherwise returns null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Default paragraph propertiies. |
| [getEffective()](#getEffective--) | Gets effective text style formatting data with the inheritance applied. |
### MaxLevelCount {#MaxLevelCount}
```
public static final byte MaxLevelCount
```


Maximum count of style levels that can be defined. Use it with \#getLevel(int).getLevel(int)

--------------------

> ```
> for (int i = 0; i < TextStyle.MaxLevelCount; i++)
>  {
>      IParagraphFormat paragraphFormat = getLevel(i);
>      ...
>  }
> ```

### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


If level of style exist returns it, otherwise returns null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Zero-based index of level. Must lay in 0..8 interval. |

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatting of level [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Default paragraph propertiies. Read-only [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Gets effective text style formatting data with the inheritance applied.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - A [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).
