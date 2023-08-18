---
title: IMathPortion
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a portion with mathematical context inside.
type: docs
weight: 914
url: /com.aspose.slides/imathportion/
---```
public interface IMathPortion
```

Represents a portion with mathematical context inside.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      MathPortion mathPortion = new MathPortion();
>      paragraph.getPortions().add(mathPortion);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Math paragraph |
### getMathParagraph() {#getMathParagraph--}
```
public abstract IMathParagraph getMathParagraph()
```


Math paragraph

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>      IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      mathParagraph.add(new MathBlock(new MathematicalText("x+y")));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)
