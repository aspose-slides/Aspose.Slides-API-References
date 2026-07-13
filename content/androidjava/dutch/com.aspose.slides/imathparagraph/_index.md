---
title: IMathParagraph
second_title: Aspose.Slides voor Android via Java API-referentie
description: Wiskundige alinea die een container is voor wiskundige blokken IMathBlock
type: docs
url: /nl/com.aspose.slides/imathparagraph/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Wiskundige alinea die een container is voor wiskundige blokken (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Standaardwaarde: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Standaardwaarde: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Slaat de inhoud van dit [IMathParagraph](../../com.aspose.slides/imathparagraph) op als MathML |
| [toLatex()](#toLatex--) | Haalt wiskundige vergelijking op in LaTeX-indeling |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Paragraph Justification Standaardwaarde: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Retour:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Paragraph Justification Standaardwaarde: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Slaat de inhoud van dit [IMathParagraph](../../com.aspose.slides/imathparagraph) op als MathML

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

Haalt wiskundige vergelijking op in LaTeX-indeling

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Retour:**
java.lang.String