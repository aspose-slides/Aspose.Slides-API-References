---
title: IMathParagraph
second_title: Aspose.Slides Androidhoz a Java API hivatkozás alapján
description: Matematikai bekezdés, amely a matematikai blokkok tárolója (IMathBlock)
type: docs
url: /hu/com.aspose.slides/imathparagraph/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Matematikai bekezdés, amely a matematikai blokkok (IMathBlock) tárolóját képezi

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification alapértelmezett érték: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification alapértelmezett érték: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | [IMathParagraph](../../com.aspose.slides/imathparagraph) tartalmát MathML formátumban menti |
| [toLatex()](#toLatex--) | Matematikai egyenletet kap LaTeX formátumban |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Paragraph Justification alapértelmezett érték: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Visszatérési érték:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Paragraph Justification alapértelmezett érték: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


[IMathParagraph](../../com.aspose.slides/imathparagraph) tartalmát MathML formátumban menti

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


Matematikai egyenletet kap LaTeX formátumban

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Visszatérési érték:**
java.lang.String