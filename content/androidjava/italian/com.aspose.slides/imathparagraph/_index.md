---
title: IMathParagraph
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Paragrafo matematico che è un contenitore per blocchi matematici IMathBlock
type: docs
url: /it/com.aspose.slides/imathparagraph/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Paragrafo matematico che è un contenitore per blocchi matematici (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Valore predefinito: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Valore predefinito: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Salva il contenuto di questo [IMathParagraph](../../com.aspose.slides/imathparagraph) come MathML |
| [toLatex()](#toLatex--) | Ottiene l'equazione matematica in formato LaTeX |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Paragraph Justification Valore predefinito: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Restituisce:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Paragraph Justification Valore predefinito: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Salva il contenuto di questo [IMathParagraph](../../com.aspose.slides/imathparagraph) come MathML

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

Ottiene l'equazione matematica in formato LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Restituisce:**
java.lang.String