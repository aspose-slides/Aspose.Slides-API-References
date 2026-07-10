---
title: IMathParagraph
second_title: Aspose.Slides for Android via Java API 参考
description: 数学段落是数学块 IMathBlock 的容器
type: docs
url: /zh/com.aspose.slides/imathparagraph/
---
**所有实现的接口:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

数学段落是数学块 (IMathBlock) 的容器

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Methods

| Method | Description |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Default value: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Default value: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Saves content of this [IMathParagraph](../../com.aspose.slides/imathparagraph) as MathML |
| [toLatex()](#toLatex--) | Gets mathematical equation in LaTeX format |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Paragraph Justification Default value: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Returns:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Paragraph Justification Default value: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Saves content of this [IMathParagraph](../../com.aspose.slides/imathparagraph) as MathML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### toLatex() {#toLatex--}
```
public abstract String toLatex()

获取 LaTeX 格式的数学方程

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**返回:**  
java.lang.String