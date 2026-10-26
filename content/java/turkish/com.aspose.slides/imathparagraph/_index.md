---
title: IMathParagraph
second_title: Aspose.Slides for Java API Referansı
description: Matematik blokları için bir kapsayıcı olan matematik paragrafı IMathBlock
type: docs
url: /tr/com.aspose.slides/imathparagraph/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Matematik blokları için bir kapsayıcı olan Matematik paragrafı (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Varsayılan değer: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Varsayılan değer: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Bu [IMathParagraph](../../com.aspose.slides/imathparagraph) içeriğini MathML olarak kaydeder |
| [toLatex()](#toLatex--) | Matematiksel denklemi LaTeX formatında alır |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Paragraph Justification Varsayılan değer: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Döndürür:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Paragraph Justification Varsayılan değer: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Bu [IMathParagraph](../../com.aspose.slides/imathparagraph) içeriğini MathML olarak kaydeder

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

Matematiksel denklemi LaTeX formatında alır

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Döndürür:**
java.lang.String