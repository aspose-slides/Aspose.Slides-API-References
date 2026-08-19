---
title: IMathParagraph
second_title: Referensi API Aspose.Slides for Java
description: Paragraf matematis yang merupakan wadah untuk blok matematika IMathBlock
type: docs
url: /id/com.aspose.slides/imathparagraph/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Paragraf matematis yang merupakan wadah untuk blok matematika (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Nilai default: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Nilai default: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Menyimpan konten dari [IMathParagraph](../../com.aspose.slides/imathparagraph) sebagai MathML |
| [toLatex()](#toLatex--) | Mendapatkan persamaan matematis dalam format LaTeX |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Paragraph Justification Nilai default: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Mengembalikan:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Paragraph Justification Nilai default: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Menyimpan konten dari [IMathParagraph](../../com.aspose.slides/imathparagraph) sebagai MathML

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream tujuan |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


Mendapatkan persamaan matematis dalam format LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Mengembalikan:**
java.lang.String