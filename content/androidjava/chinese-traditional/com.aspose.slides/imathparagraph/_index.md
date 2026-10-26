---
title: IMathParagraph
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 數學段落，用於容納數學區塊 IMathBlock
type: docs
url: /zh-hant/com.aspose.slides/imathparagraph/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

數學段落，作為數學區塊 (IMathBlock) 的容器

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification 預設值: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification 預設值: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 將此 [IMathParagraph](../../com.aspose.slides/imathparagraph) 的內容儲存為 MathML |
| [toLatex()](#toLatex--) | 取得 LaTeX 格式的數學方程式 |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Paragraph Justification 預設值: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**返回:**  
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Paragraph Justification 預設值: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

將此 [IMathParagraph](../../com.aspose.slides/imathparagraph) 的內容儲存為 MathML

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

取得 LaTeX 格式的數學方程式

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