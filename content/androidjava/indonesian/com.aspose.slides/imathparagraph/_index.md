---
title: IMathParagraph
second_title: Aspose.Slides untuk Android melalui Referensi API Java
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
> Contoh:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Metode

| Method | Description |
| --- | --- |
| [getJustification()](#getJustification--) | Justifikasi Paragraf Nilai Default: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Justifikasi Paragraf Nilai Default: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Menyimpan konten dari [IMathParagraph](../../com.aspose.slides/imathparagraph) ini sebagai MathML |
| [toLatex()](#toLatex--) | Mendapatkan persamaan matematis dalam format LaTeX |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Justifikasi Paragraf Nilai Default: CenteredAsGroup

--------------------

> ```
> Contoh:
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


Justifikasi Paragraf Nilai Default: CenteredAsGroup

--------------------

> ```
> Contoh:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Menyimpan konten dari [IMathParagraph](../../com.aspose.slides/imathparagraph) ini sebagai MathML

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


Mendapatkan persamaan matematis dalam format LaTeX

--------------------

> ```
> Contoh:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Mengembalikan:**
java.lang.String