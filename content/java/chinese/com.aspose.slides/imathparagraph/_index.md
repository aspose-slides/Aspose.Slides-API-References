---
title: IMathParagraph
second_title: Aspose.Slides for Java API 参考
description: 用于容纳数学块 IMathBlock 的数学段落
type: docs
url: /zh/com.aspose.slides/imathparagraph/
---
**所有实现的接口：**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

数学段落，是数学块 (IMathBlock) 的容器

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification 默认值: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification 默认值: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 保存此 [IMathParagraph](../../com.aspose.slides/imathparagraph) 的内容为 MathML |
| [toLatex()](#toLatex--) | 获取 LaTeX 格式的数学公式 |

### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Paragraph Justification 默认值: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**返回：**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Paragraph Justification 默认值: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

保存此 [IMathParagraph](../../com.aspose.slides/imathparagraph) 的内容为 MathML

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

获取 LaTeX 格式的数学公式

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**返回：**
java.lang.String