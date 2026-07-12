---
title: MathPortion
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Matematiksel bağlam içeren bir bölümü temsil eder.
type: docs
url: /tr/com.aspose.slides/mathportion/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Matematiksel bağlam içeren bir bölümü temsil eder.

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

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathPortion()](#MathPortion--) | MathPortion sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Matematik paragrafı |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

MathPortion sınıfının yeni bir örneğini başlatır.

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

Matematik paragrafı

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


**Döndürür:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)