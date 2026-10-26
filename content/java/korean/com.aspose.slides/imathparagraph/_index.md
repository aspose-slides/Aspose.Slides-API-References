---
title: IMathParagraph
second_title: Aspose.Slides for Java API 참조
description: 수학 블록 IMathBlock을 담는 컨테이너인 수학 단락
type: docs
url: /ko/com.aspose.slides/imathparagraph/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

수학 블록을 담는 컨테이너인 수학 단락 (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification 기본값: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification 기본값: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 이 [IMathParagraph](../../com.aspose.slides/imathparagraph)의 내용을 MathML로 저장합니다 |
| [toLatex()](#toLatex--) | LaTeX 형식의 수학 방정식을 가져옵니다 |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Paragraph Justification 기본값: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**반환값:** 
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Paragraph Justification 기본값: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


이 [IMathParagraph](../../com.aspose.slides/imathparagraph)의 내용을 MathML로 저장합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


LaTeX 형식의 수학 방정식을 가져옵니다

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**반환값:**
java.lang.String