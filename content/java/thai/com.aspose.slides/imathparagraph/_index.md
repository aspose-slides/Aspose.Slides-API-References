---
title: IMathParagraph
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: ย่อหน้าคณิตศาสตร์ที่เป็นคอนเทนเนอร์สำหรับบล็อกคณิตศาสตร์ IMathBlock
type: docs
url: /th/com.aspose.slides/imathparagraph/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

ย่อหน้าคณิตศาสตร์ที่เป็นคอนเทนเนอร์สำหรับบล็อกคณิตศาสตร์ (IMathBlock)

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
| [getJustification()](#getJustification--) | Paragraph Justification ค่าเริ่มต้น: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification ค่าเริ่มต้น: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | บันทึกเนื้อหาของ [IMathParagraph](../../com.aspose.slides/imathparagraph) นี้เป็น MathML |
| [toLatex()](#toLatex--) | รับสมการคณิตศาสตร์ในรูปแบบ LaTeX |

### getJustification() {#getJustification--}
```
public abstract int getJustification()
```

Paragraph Justification ค่าเริ่มต้น: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```


**ค่าที่ส่งคืน:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```

Paragraph Justification ค่าเริ่มต้น: CenteredAsGroup

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

บันทึกเนื้อหาของ [IMathParagraph](../../com.aspose.slides/imathparagraph) นี้เป็น MathML

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```

รับสมการคณิตศาสตร์ในรูปแบบ LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```


**ค่าที่ส่งคืน:**
java.lang.String