---
title: IMathPortion
second_title: Aspose.Slides for Android via Java API 参考
description: 表示具有数学上下文的部分。
type: docs
url: /zh/com.aspose.slides/imathportion/
---
```
public interface IMathPortion
```

表示具有数学上下文的部分。

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

数学段落

--------------------

> ```
> 示例：
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

**返回值：**
[IMathParagraph](../../com.aspose.slides/imathparagraph)