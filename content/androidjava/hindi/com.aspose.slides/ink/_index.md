---
title: Ink
second_title: Android के लिए Aspose.Slides, Java API रेफ़रेंस द्वारा
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

स्लाइड पर एक इंक ऑब्जेक्ट का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTraces()](#getTraces--) | IInk तत्व [IInkTrace](../../com.aspose.slides/iinktrace) में मौजूद सभी ट्रेस को प्राप्त करता है। |
| [getInkEffectImages()](#getInkEffectImages--) | इंक ब्रश के लिए दृश्य प्रभावों का अनुकरण करने के लिए उपयोग की जाने कस्टम इमेज संग्रह को प्राप्त करता है। |

### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

IInk तत्व [IInkTrace](../../com.aspose.slides/iinktrace) में मौजूद सभी ट्रेस को प्राप्त करता है। केवल-पढ़ने योग्य।

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

इंक ब्रश के लिए दृश्य प्रभावों का अनुकरण करने के लिए उपयोग की जाने कस्टम इमेज संग्रह को प्राप्त करता है। ये इमेज उन विशिष्ट [InkEffectType](../../com.aspose.slides/inkeffecttype) मानों के साथ इंक को रेंडर करने पर उपयोग होते हैं, जैसे Galaxy, Rainbow आदि। अपनी स्वयं की इमेज प्रदान करके, आप नियंत्रित कर सकते हैं कि प्रत्येक इंक प्रभाव कैसे प्रदर्शित होता है।

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

यह गुण आपको डिफ़ॉल्ट इंक प्रभाव टेक्सचर को उपयोगकर्ता-परिभाषित के साथ बदलने की अनुमति देता है, जो विशेष रूप से उपयोगी है जब लाइसेंसिंग द्वारा डिफ़ॉल्ट एसेट प्रतिबंधित होते हैं या रनटाइम पर उपलब्ध नहीं होते। शब्दकोश में प्रत्येक प्रविष्टि को एक [InkEffectType](../../com.aspose.slides/inkeffecttype) मान को संबंधित [IImage](../../com.aspose.slides/iimage) ऑब्जेक्ट (उदाहरण के लिए, Bitmap, या Aspose इमेज इंटरफ़ेस) के साथ जोड़ना चाहिए।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>