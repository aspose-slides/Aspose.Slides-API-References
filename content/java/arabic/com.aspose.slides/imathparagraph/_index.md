---
title: IMathParagraph
second_title: مرجع API لـ Aspose.Slides للغة Java
description: فقرة رياضية تكون حاوية للكتل الرياضية IMathBlock
type: docs
url: /ar/com.aspose.slides/imathparagraph/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

فقرة رياضية تكون حاوية للكتل الرياضية (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getJustification()](#getJustification--) | محاذاة الفقرة القيمة الافتراضية: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | محاذاة الفقرة القيمة الافتراضية: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | يحفظ محتوى هذا [IMathParagraph](../../com.aspose.slides/imathparagraph) بصيغة MathML |
| [toLatex()](#toLatex--) | يحصل على المعادلة الرياضية بصيغة LaTeX |

### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

محاذاة الفقرة القيمة الافتراضية: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**القيمة المرجعة:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

محاذاة الفقرة القيمة الافتراضية: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

يحفظ محتوى هذا [IMathParagraph](../../com.aspose.slides/imathparagraph) بصيغة MathML

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

يحصل على المعادلة الرياضية بصيغة LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**القيمة المرجعة:**
java.lang.String