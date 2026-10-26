---
title: MathPortion
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر بخشی با زمینه ریاضی داخل است.
type: docs
url: /fa/com.aspose.slides/mathportion/
---
**ارث-برداری:**  
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**تمام واسط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)  
```
public final class MathPortion extends Portion implements IMathPortion
```

نمایانگر بخشی با زمینهٔ ریاضی داخل است.

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
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [MathPortion()](#MathPortion--) | یک نمونه جدید از کلاس MathPortion را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | پاراگراف ریاضی |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

یک نمونه جدید از کلاس MathPortion را مقداردهی اولیه می‌کند.

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

پاراگراف ریاضی

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

**بازگرداندن:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph)