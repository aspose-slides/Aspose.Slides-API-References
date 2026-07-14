---
title: MathPortion
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงส่วนที่มีบริบททางคณิตศาสตร์ภายใน.
type: docs
url: /th/com.aspose.slides/mathportion/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

แสดงส่วนที่มีบริบททางคณิตศาสตร์ภายใน.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>  	 IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>  	 IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>  	 MathPortion mathPortion = new MathPortion();
>  	 paragraph.getPortions().add(mathPortion);
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathPortion()](#MathPortion--) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathPortion |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | ย่อหน้าคณิตศาสตร์ |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```


เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathPortion.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>  	 IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>  	 IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>  	 MathPortion mathPortion = new MathPortion();
>  	 paragraph.getPortions().add(mathPortion);
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

### getMathParagraph() {#getMathParagraph--}
```
public final IMathParagraph getMathParagraph()
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