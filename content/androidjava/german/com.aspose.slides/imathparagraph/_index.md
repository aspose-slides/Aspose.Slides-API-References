---
title: IMathParagraph
second_title: Aspose.Slides für Android über Java API-Referenz
description: Mathematischer Absatz, der ein Container für mathematische Blöcke ist IMathBlock
type: docs
url: /de/com.aspose.slides/imathparagraph/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Mathematischer Absatz, der ein Container für mathematische Blöcke ist (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Standardwert: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Standardwert: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Speichert den Inhalt dieses [IMathParagraph](../../com.aspose.slides/imathparagraph) als MathML |
| [toLatex()](#toLatex--) | Erhält mathematische Gleichung im LaTeX-Format |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Paragraph Justification Standardwert: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Rückgabe:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Paragraph Justification Standardwert: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Speichert den Inhalt dieses [IMathParagraph](../../com.aspose.slides/imathparagraph) als MathML

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Zielstream |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

Erhält mathematische Gleichung im LaTeX-Format

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Rückgabe:**
java.lang.String