---
title: MathPortion
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफ़रेंस के माध्यम से
description: गणितीय संदर्भ के साथ एक भाग को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/mathportion/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

गणितीय संदर्भ के साथ एक भाग को दर्शाता है।

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
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathPortion()](#MathPortion--) | MathPortion क्लास का नया उदाहरण आरंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | गणित पैराग्राफ |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```


MathPortion क्लास का नया उदाहरण आरंभ करता है।

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


गणित पैराग्राफ

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