---
title: MathPortion
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili bagian dengan konteks matematika di dalamnya.
type: docs
url: /id/com.aspose.slides/mathportion/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Mewakili bagian dengan konteks matematika di dalamnya.

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
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathPortion()](#MathPortion--) | Menginisialisasi sebuah instance baru dari kelas MathPortion. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Paragraf matematika |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```


Menginisialisasi sebuah instance baru dari kelas MathPortion.

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


Paragraf matematika

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

**Mengembalikan:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)