---
title: IMathPortion
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงส่วนที่มีบริบททางคณิตศาสตร์ภายใน.
type: docs
url: /th/com.aspose.slides/imathportion/
---```
public interface IMathPortion
```

แสดงส่วนที่มีบริบททางคณิตศาสตร์ภายใน.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      MathPortion mathPortion = new MathPortion();
>      paragraph.getPortions().add(mathPortion);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | ย่อหน้าคณิตศาสตร์ |
### getMathParagraph() {#getMathParagraph--}
```
public abstract IMathParagraph getMathParagraph()
```


ย่อหน้าคณิตศาสตร์

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>      IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      mathParagraph.add(new MathBlock(new MathematicalText("x+y")));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)