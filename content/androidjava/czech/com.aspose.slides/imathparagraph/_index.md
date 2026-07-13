---
title: IMathParagraph
second_title: Aspose.Slides pro Android – referenční příručka Java API
description: Matematický odstavec, který je kontejnerem pro matematické bloky IMathBlock
type: docs
url: /cs/com.aspose.slides/imathparagraph/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Matematický odstavec, který je kontejnerem pro matematické bloky (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getJustification()](#getJustification--) | Výchozí hodnota zarovnání odstavce: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Výchozí hodnota zarovnání odstavce: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Uloží obsah tohoto [IMathParagraph](../../com.aspose.slides/imathparagraph) jako MathML |
| [toLatex()](#toLatex--) | Získá matematickou rovnici ve formátu LaTeX |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Výchozí hodnota zarovnání odstavce: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Vrací:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Výchozí hodnota zarovnání odstavce: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustized);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Uloží obsah tohoto [IMathParagraph](../../com.aspose.slides/imathparagraph) jako MathML

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


Získá matematickou rovnici ve formátu LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Vrací:**
java.lang.String