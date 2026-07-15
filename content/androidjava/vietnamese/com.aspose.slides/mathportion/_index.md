---
title: MathPortion
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn một phần có ngữ cảnh toán học bên trong.
type: docs
url: /vi/com.aspose.slides/mathportion/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Biểu diễn một phần với ngữ cảnh toán học bên trong.

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
## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [MathPortion()](#MathPortion--) | Khởi tạo một thực thể mới của lớp MathPortion. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Đoạn toán học |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

Khởi tạo một thực thể mới của lớp MathPortion.

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

Đoạn toán học

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

**Trả về:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)