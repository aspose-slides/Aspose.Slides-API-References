---
title: MathPortion
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: गणितीय संदर्भ के साथ एक भाग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/mathportion/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**All Implemented Interfaces:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

गणितीय संदर्भ के साथ एक भाग का प्रतिनिधित्व करता है।

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
## कन्स्ट्रक्टर

| Constructor | Description |
| --- | --- |
| [MathPortion()](#MathPortion--) | MathPortion class का एक नया उदाहरण प्रारम्भ करता है। |
## विधियाँ

| Method | Description |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | गणित अनुच्छेद |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```


MathPortion class का एक नया उदाहरण प्रारम्भ करता है।

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


गणित अनुच्छेद

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

**रिटर्न:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)