---
title: Compress
second_title: Aspose.Slides for Java API संदर्भ
description: प्रस्तुति को संपीड़ित करने के इरादे से बनी विधियों के समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/compress/
---
**विरासत:**
java.lang.Object
```
public class Compress
```

[Presentation](../../com.aspose.slides/presentation) को संपीड़ित करने के लिए अभिप्रेत विधियों के एक समूह का प्रतिनिधित्व करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Compress()](#Compress--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | प्रस्तुति का आकार सभी उपलब्ध संपीड़न चरणों को लागू करके घटाता है:

 *  अप्रयुक्त मास्टर स्लाइड्स को हटाता है \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  अप्रयुक्त लेआउट स्लाइड्स को हटाता है \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  एम्बेडेड फ़ॉन्ट्स में वास्तव में उपयोग किए गए ग्लिफ़्स को ही रखता है \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  चित्रों का रिज़ॉल्यूशन 150 DPI तक घटाता है और क्रॉप किए हुए क्षेत्रों को हटा देता है \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) का संपीड़न अप्रयुक्त मास्टर स्लाइड्स को हटाकर करता है। |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) का संपीड़न अप्रयुक्त लेआउट स्लाइड्स को हटाकर करता है। |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) का संपीड़न एम्बेडेड फ़ॉन्ट्स से अप्रयुक्त अक्षरों को हटाकर करता है। |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | प्रेजेंटेशन में चित्रों का रिज़ॉल्यूशन घटाता है और उनके क्रॉप किए गए क्षेत्रों को हटा देता है, जैसा कि PowerPoint के "Compress Pictures" के समान सभी चित्रों पर लागू होता है। |
### Compress() {#Compress--}
```
public Compress()
```

### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```

प्रस्तुति का आकार सभी उपलब्ध संपीड़न चरणों को लागू करके घटाता है:

 *  अप्रयुक्त मास्टर स्लाइड्स को हटाता है \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  अप्रयुक्त लेआउट स्लाइड्स को हटाता है \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  एम्बेडेड फ़ॉन्ट्स में वास्तव में उपयोग किए गए ग्लिफ़्स को ही रखता है \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  चित्रों का रिज़ॉल्यूशन 150 DPI तक घटाता है और क्रॉप किए हुए क्षेत्रों को हटा देता है \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पर्याय:**
| पर्याय | टाइप | विवरण |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | संकुचित करने के लिए प्रस्तुति। |

संपीड़न को अनुकूलित करने के लिए, उदाहरण के लिए अलग चित्र रिज़ॉल्यूशन का उपयोग करने या किसी चरण को छोड़ने के लिए, ऊपर सूचीबद्ध मेथड्स को इस एक के बजाय व्यक्तिगत रूप से कॉल करें। चित्रों के क्रॉप किए गए क्षेत्रों को स्थायी रूप से हटा दिया जाता है और उन्हें PowerPoint में पुनर्स्थापित नहीं किया जा सकता। |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) का संपीड़न अप्रयुक्त मास्टर स्लाइड्स को हटाकर करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पर्याय:**
| पर्याय | टाइप | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | प्रस्तुति का उदाहरण |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) का संपीड़न अप्रयुक्त लेआउट स्लाइड्स को हटाकर करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पर्याय:**
| पर्याय | टाइप | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | प्रस्तुति का उदाहरण |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) का संपीड़न एम्बेडेड फ़ॉन्ट्स से अप्रयुक्त अक्षरों को हटाकर करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पर्याय:**
| पर्याय | टाइप | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | प्रस्तुति का उदाहरण |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```

प्रेजेंटेशन में चित्रों का रिज़ॉल्यूशन घटाता है और उनके क्रॉप किए गए क्षेत्रों को हटा देता है, जैसा कि PowerPoint के "Compress Pictures" के समान सभी चित्रों पर लागू होता है। स्लाइड्स, लेआउट स्लाइड्स और मास्टर स्लाइड्स पर चित्र प्रोसेस किए जाते हैं, जिसमें समूह आकारों के भीतर के चित्र और आकारों की पिक्चर फिल्स शामिल हैं।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पर्याय:**
| पर्याय | टाइप | विवरण |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | प्रक्रिया करने के लिए प्रस्तुति। |
| resolution | int | प्रत्येक चित्र के प्रदर्शित आकार के सापेक्ष लक्ष्य रिज़ॉल्यूशन। [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) चित्रों को अपरिवर्तित छोड़ता है। |

लक्ष्य रिज़ॉल्यूशन पर या उससे नीचे की चित्रों को अपरिवर्तित छोड़ दिया जाता है; चित्रों को कभी अपस्केल नहीं किया जाता।

प्रक्रिया नहीं की गई: स्लाइड बैकग्राउंड, टेबल सेल फिल्स, चार्ट्स, SmartArt, GIF चित्र (एनिमेशन संरक्षित रखने के लिए), SVG और मे्टाफाइल (EMF/WMF) चित्र।

क्रॉप किए गए क्षेत्रों को स्थायी रूप से हटा दिया जाता है और उन्हें PowerPoint में पुनर्स्थापित नहीं किया जा सकता। |