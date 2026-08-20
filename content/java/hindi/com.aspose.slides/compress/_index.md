---
title: Compress
second_title: Aspose.Slides के लिए Java API संदर्भ
description: संकुचित करने के लिए अभिप्रेत विधियों का समूह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/compress/
---
**विरासत:**  
java.lang.Object  
```
public class Compress
```

एक समूह विधियों का प्रतिनिधित्व करता है जिसका उद्देश्य [Presentation](../../com.aspose.slides/presentation) को संकुचित करना है।

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
## निर्माणकर्ता

| निर्माता | विवरण |
| --- | --- |
| [Compress()](#Compress--) |  |
## विधियां

| विधि | विवरण |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | अनुपयोगी मास्टर स्लाइड्स को हटाकर [Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है। |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | अनुपयोगी लेआउट स्लाइड्स को हटाकर [Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है। |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | एम्बेडेड फ़ॉन्ट्स से अनुपयोगी अक्षरों को हटाकर [Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है। |
### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

अनुपयोगी मास्टर स्लाइड्स को हटाकर [Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | प्रेज़ेंटेशन उदाहरण |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

अनुपयोगी लेआउट स्लाइड्स को हटाकर [Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | प्रेज़ेंटेशन उदाहरण |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

एम्बेडेड फ़ॉन्ट्स से अनुपयोगी अक्षरों को हटाकर [Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | प्रेज़ेंटेशन उदाहरण |