---
title: MathPortion
second_title: Aspose.Slides for Android via Java API 参考
description: 表示具有数学上下文的片段。
type: docs
url: /zh/com.aspose.slides/mathportion/
---
**继承：**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**所有实现的接口：**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

表示具有数学上下文的片段。

--------------------

> ```
> 示例：
>  
>  Presentation pres = new Presentation();
>  try {
>  	 IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>  	 IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>  	 MathPortion mathPortion = new MathPortion();
>  	 paragraph.getPortions().add(mathPortion);
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathPortion()](#MathPortion--) | Initializes a new instance of the MathPortion class. |
## Methods

| Method | Description |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Math paragraph |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

Initializes a new instance of the MathPortion class.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>  	 IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>  	 IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>  	 MathPortion mathPortion = new MathPortion();
>  	 paragraph.getPortions().add(mathPortion);
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

### getMathParagraph() {#getMathParagraph--}
```
public final IMathParagraph getMathParagraph()

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