---
title: IMathParagraph
second_title: Aspose.Slides for Java API referencia
description: Matematikai bekezdés, amely a matematikai blokkok (IMathBlock) tárolója
type: docs
url: /hu/com.aspose.slides/imathparagraph/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Matematikai bekezdés, amely a matematikai blokkok (IMathBlock) tárolója

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getJustification()](#getJustification--) | Bekezdés igazítása Alapértelmezett érték: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Bekezdés igazítása Alapértelmezett érték: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | A(z) [IMathParagraph](../../com.aspose.slides/imathparagraph) tartalmát MathML-ként menti |
| [toLatex()](#toLatex--) | Matematikai egyenletet ad vissza LaTeX formátumban |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Bekezdés igazítása Alapértelmezett érték: CenteredAsGroup

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


Bekezdés igazítása Alapértelmezett érték: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


A(z) [IMathParagraph](../../com.aspose.slides/imathparagraph) tartalmát MathML-ként menti

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


Matematikai egyenletet ad vissza LaTeX formátumban

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