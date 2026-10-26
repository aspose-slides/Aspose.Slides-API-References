---
title: IMathParagraph
second_title: مرجع API جاوا برای Aspose.Slides برای اندروید
description: پاراگراف ریاضی که یک مخزن برای بلوک‌های ریاضی IMathBlock است
type: docs
url: /fa/com.aspose.slides/imathparagraph/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

پاراگراف ریاضی که یک مخزن برای بلوک‌های ریاضی است (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification مقدار پیش‌فرض: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification مقدار پیش‌فرض: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | محتویات این [IMathParagraph](../../com.aspose.slides/imathparagraph) را به صورت MathML ذخیره می‌کند |
| [toLatex()](#toLatex--) | معادله ریاضی را در قالب LaTeX دریافت می‌کند |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Paragraph Justification مقدار پیش‌فرض: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**بازگشت:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Paragraph Justification مقدار پیش‌فرض: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

محتویات این [IMathParagraph](../../com.aspose.slides/imathparagraph) را به صورت MathML ذخیره می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

معادله ریاضی را در قالب LaTeX دریافت می‌کند

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**بازگشت:**
java.lang.String