---
title: IMathParagraph
second_title: Referencia de API de Aspose.Slides para Java
description: Párrafo matemático que es un contenedor de bloques matemáticos IMathBlock
type: docs
url: /es/com.aspose.slides/imathparagraph/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Párrafo matemático que es un contenedor de bloques matemáticos (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
```
## Métodos

| Method | Description |
| --- | --- |
| [getJustification()](#getJustification--) | Justificación del Paragraph Valor predeterminado: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Justificación del Paragraph Valor predeterminado: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Guarda el contenido de este [IMathParagraph](../../com.aspose.slides/imathparagraph) como MathML |
| [toLatex()](#toLatex--) | Obtiene la ecuación matemática en formato LaTeX |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Justificación del Paragraph Valor predeterminado: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Devuelve:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Justificación del Paragraph Valor predeterminado: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Guarda el contenido de este [IMathParagraph](../../com.aspose.slides/imathparagraph) como MathML

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


Obtiene la ecuación matemática en formato LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Devuelve:**
java.lang.String