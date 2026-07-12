---
title: IMathParagraph
second_title: Java API リファレンスを使用した Android 向け Aspose.Slides
description: 数式ブロック (IMathBlock) のコンテナである数式段落
type: docs
url: /ja/com.aspose.slides/imathparagraph/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

数式ブロックのコンテナである数式段落 (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification デフォルト値: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification デフォルト値: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | この[IMathParagraph](../../com.aspose.slides/imathparagraph)の内容を MathML として保存します |
| [toLatex()](#toLatex--) | LaTeX 形式の数式を取得します |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Paragraph Justification デフォルト値: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**戻り値:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Paragraph Justification デフォルト値: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


この[IMathParagraph](../../com.aspose.slides/imathparagraph)の内容を MathML として保存します

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


LaTeX 形式の数式を取得します

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**戻り値:**
java.lang.String