---
title: IMathParagraph
second_title: Aspose.Slides för Android via Java API-referens
description: Matematiskt stycke som är en behållare för matematiska block IMathBlock
type: docs
url: /sv/com.aspose.slides/imathparagraph/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Matematisk stycke som är en behållare för matematiska block (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getJustification()](#getJustification--) | Standardvärde för styckejustering: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Standardvärde för styckejustering: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Sparar innehållet i detta [IMathParagraph](../../com.aspose.slides/imathparagraph) som MathML |
| [toLatex()](#toLatex--) | Hämtar matematisk ekvation i LaTeX-format |

### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Standardvärde för styckejustering: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Returnerar:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Standardvärde för styckejustering: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Sparar innehållet i detta [IMathParagraph](../../com.aspose.slides/imathparagraph) som MathML

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målström |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

Hämtar matematisk ekvation i LaTeX-format

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Returnerar:**
java.lang.String