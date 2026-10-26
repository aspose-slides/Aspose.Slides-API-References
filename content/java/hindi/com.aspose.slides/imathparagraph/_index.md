---
title: IMathParagraph
second_title: Aspose.Slides जावा API रेफ़रेंस
description: गणितीय अनुच्छेद जो गणितीय ब्लॉकों IMathBlock के लिए कंटेनर है
type: docs
url: /hi/com.aspose.slides/imathparagraph/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

गणितीय अनुच्छेद जो गणितीय ब्लॉकों (IMathBlock) के लिए कंटेनर है

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getJustification()](#getJustification--) | पैराग्राफ संरेखण डिफ़ॉल्ट मान: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | पैराग्राफ संरेखण डिफ़ॉल्ट मान: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | इस [IMathParagraph](../../com.aspose.slides/imathparagraph) की सामग्री को MathML के रूप में सहेजता है |
| [toLatex()](#toLatex--) | LaTeX स्वरूप में गणितीय समीकरण प्राप्त करता है |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

पैराग्राफ संरेखण डिफ़ॉल्ट मान: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**रिटर्न मान:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

पैराग्राफ संरेखण डिफ़ॉल्ट मान: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

इस [IMathParagraph](../../com.aspose.slides/imathparagraph) की सामग्री को MathML के रूप में सहेजता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

LaTeX स्वरूप में गणितीय समीकरण प्राप्त करता है

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**रिटर्न मान:**
java.lang.String