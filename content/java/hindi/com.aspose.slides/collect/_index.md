---
title: Collect
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: विभिन्न प्रकार के मॉडल ऑब्जेक्ट्स को एकत्र करने के उद्देश्य से विधियों के समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/collect/
---
**विरासत:**
java.lang.Object
```
public class Collect
```

विभिन्न प्रकार के मॉडल ऑब्जेक्ट्स को [Presentation](../../com.aspose.slides/presentation) से एकत्र करने हेतु विधियों के समूह का प्रतिनिधित्व करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... आकार फ़ॉर्मेटिंग या अन्य गुणों को बदलें
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Collect()](#Collect--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | [Shape](../../com.aspose.slides/shape) के सभी उदाहरणों को [Presentation](../../com.aspose.slides/presentation) में एकत्र करता है। |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

[Shape](../../com.aspose.slides/shape) के सभी उदाहरणों को [Presentation](../../com.aspose.slides/presentation) में एकत्र करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // यदि shape AutoShape है, तो काली ठोस सीमा जोड़ें
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | आकृतियों को एकत्र करने के लिए प्रस्तुति |

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - प्रस्तुति में स्थित सभी आकृतियों का संग्रह