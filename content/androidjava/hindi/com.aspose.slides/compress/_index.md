---
title: Compress
second_title: Aspose.Slides for Android Java API संदर्भ के माध्यम से
description: एक समूह विधियों को दर्शाता है जिसका उद्देश्य संपीड़ित करना है।
type: docs
url: /hi/com.aspose.slides/compress/
---
**विरासत:**  
java.lang.Object
```
public class Compress
```

[Presentation](../../com.aspose.slides/presentation) को संपीड़ित करने हेतु अभिप्रेत विधियों का एक समूह दर्शाता है।

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

| निर्माता | विवरण |
| --- | --- |
| [Compress()](#Compress--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है, अप्रयुक्त मास्टर स्लाइड्स को हटाकर। |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है, अप्रयुक्त लेआउट स्लाइड्स को हटाकर। |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है, एम्बेडेड फ़ॉन्ट्स से अप्रयुक्त अक्षरों को हटाकर। |
### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है, अप्रयुक्त मास्टर स्लाइड्स को हटाकर।

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation का उदाहरण |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है, अप्रयुक्त लेआउट स्लाइड्स को हटाकर।

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation का उदाहरण |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) का संपीड़न करता है, एम्बेडेड फ़ॉन्ट्स से अप्रयुक्त अक्षरों को हटाकर।

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation का उदाहरण |