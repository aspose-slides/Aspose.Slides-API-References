---
title: Collect
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: विभिन्न प्रकार के मॉडल ऑब्जेक्ट्स को . से एकत्र करने के उद्देश्य वाले मेथड्स के समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/collect/
---
**विरासत:**
java.lang.Object
```
public class Collect
```

विभिन्न प्रकार की मॉडल वस्तुओं को [Presentation](../../com.aspose.slides/presentation) से एकत्र करने के उद्देश्य वाले मेथड्स के समूह का प्रतिनिधित्व करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... आकार की स्वरूपण या अन्य गुण बदलें
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Collect()](#Collect--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | [Shape](../../com.aspose.slides/shape) की सभी इंस्टेंस [Presentation](../../com.aspose.slides/presentation) में एकत्र करता है। |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

[Shape](../../com.aspose.slides/shape) की सभी इंस्टेंस [Presentation](../../com.aspose.slides/presentation) में एकत्र करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | शेप्स एकत्र करने के लिए प्रस्तुति |

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - प्रस्तुति में मौजूद सभी शेप्स का संग्रह