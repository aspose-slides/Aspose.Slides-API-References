---
title: IMathParagraph
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: ย่อหน้าทางคณิตศาสตร์ที่เป็นตัวบรรจุของบล็อกทางคณิตศาสตร์ IMathBlock
type: docs
url: /th/com.aspose.slides/imathparagraph/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

ย่อหน้าทางคณิตศาสตร์ที่เป็นตัวบรรจุของบล็อกทางคณิตศาสตร์ (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification ค่าตั้งต้น: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification ค่าตั้งต้น: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | บันทึกเนื้อหาของ [IMathParagraph](../../com.aspose.slides/imathparagraph) เป็น MathML |
| [toLatex()](#toLatex--) | รับสมการทางคณิตศาสตร์ในรูปแบบ LaTeX |

### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Paragraph Justification ค่าตั้งต้น: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**คืนค่า:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Paragraph Justification ค่าตั้งต้น: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

บันทึกเนื้อหาของ [IMathParagraph](../../com.aspose.slides/imathparagraph) เป็น MathML

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

รับสมการทางคณิตศาสตร์ในรูปแบบ LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**คืนค่า:**
java.lang.String