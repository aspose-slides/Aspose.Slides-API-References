---
title: IMathParagraph
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Μαθηματική παράγραφος που είναι υποδοχείο για μαθηματικά μπλοκ IMathBlock
type: docs
url: /el/com.aspose.slides/imathparagraph/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Μαθηματική παράγραφος που αποτελεί container για μαθηματικά blocks (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Προεπιλεγμένη τιμή: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Προεπιλεγμένη τιμή: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο αυτής [IMathParagraph](../../com.aspose.slides/imathparagraph) ως MathML |
| [toLatex()](#toLatex--) | Παίρνει μαθηματική εξίσωση σε μορφή LaTeX |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Paragraph Justification Προεπιλεγμένη τιμή: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Επιστρέφει:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Paragraph Justification Προεπιλεγμένη τιμή: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Αποθηκεύει το περιεχόμενο αυτής [IMathParagraph](../../com.aspose.slides/imathparagraph) ως MathML

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή προορισμού |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


Παίρνει μαθηματική εξίσωση σε μορφή LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Επιστρέφει:**
java.lang.String