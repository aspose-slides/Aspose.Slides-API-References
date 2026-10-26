---
title: Ink
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक स्लाइड पर इंक ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ink/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

एक स्लाइड पर इंक ऑब्जेक्ट का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTraces()](#getTraces--) | IInk तत्व [IInkTrace](../../com.aspose.slides/iinktrace) में मौजूद सभी ट्रेस प्राप्त करता है। |
| [getInkEffectImages()](#getInkEffectImages--) | इंक ब्रश के लिए दृश्य प्रभावों का अनुकरण करने हेतु उपयोग की जाने कस्टम छवियों का संग्रह प्राप्त करता है। |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

IInk तत्व [IInkTrace](../../com.aspose.slides/iinktrace) में मौजूद सभी ट्रेस प्राप्त करता है। केवल-पढ़ने योग्य।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

इंक ब्रश के लिए दृश्य प्रभावों का अनुकरण करने हेतु उपयोग की जाने कस्टम छवियों का संग्रह प्राप्त करता है। ये छवियां विशिष्ट [InkEffectType](../../com.aspose.slides/inkeffecttype) मानों, जैसे Galaxy, Rainbow, आदि के साथ इंक को रेंडर करते समय उपयोग होती हैं। अपनी खुद की छवियां प्रदान करके आप प्रत्येक इंक प्रभाव की उपस्थिति को नियंत्रित कर सकते हैं।

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

यह गुण डिफ़ॉल्ट इंक इफ़ेक्ट टेक्सचर को उपयोगकर्ता-परिभाषित टेक्सचर से बदलने की सुविधा देता है, जो विशेष रूप से तब उपयोगी होता है जब लाइसेंसिंग के कारण डिफ़ॉल्ट संसाधन प्रतिबंधित या रनटाइम में उपलब्ध नहीं होते। शब्दकोश में प्रत्येक प्रविष्टि को एक [InkEffectType](../../com.aspose.slides/inkeffecttype) मान को संबंधित [IImage](../../com.aspose.slides/iimage) ऑब्जेक्ट (जैसे Bitmap, या Aspose इमेज इंटरफ़ेस) के साथ संबद्ध करना चाहिए।

**वापसी:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>