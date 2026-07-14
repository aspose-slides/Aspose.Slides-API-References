---
title: IMathParagraph
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: गणितीय पैराग्राफ जो गणितीय ब्लॉकों IMathBlock के लिए कंटेनर है
type: docs
url: /hi/com.aspose.slides/imathparagraph/
---
**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

गणितीय पैराग्राफ जो गणितीय ब्लॉकों (IMathBlock) के लिए कंटेनर है

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
| [getJustification()](#getJustification--) | Paragraph Justification डिफ़ॉल्ट मान: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification डिफ़ॉल्ट मान: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Saves content of this [IMathParagraph](../../com.aspose.slides/imathparagraph) as MathML |
| [toLatex()](#toLatex--) | Gets mathematical equation in LaTeX format |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Paragraph Justification डिफ़ॉल्ट मान: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**वापसी मान:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Paragraph Justification डिफ़ॉल्ट मान: CenteredAsGroup

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


LaTeX फ़ॉर्मेट में गणितीय समीकरण प्राप्त करता है

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**वापसी मान:**
java.lang.String