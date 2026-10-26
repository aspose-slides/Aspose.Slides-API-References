---
title: FontsLoader
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: उपयोगकर्ता द्वारा परिभाषित कस्टम फ़ॉन्ट लोड करने के लिए क्लास।
type: docs
url: /hi/com.aspose.slides/fontsloader/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)  
```
public final class FontsLoader implements IFontsLoader
```

उपयोगकर्ता द्वारा परिभाषित कस्टम फ़ॉन्ट लोड करने के लिए क्लास। इसे किसी भी प्रस्तुति वस्तु को बनाने से पहले उपयोग किया जाना चाहिए।
## Methods

| मेथड | विवरण |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Adds additional folders to seek fonts. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Adds font from the binary data |
| [getFontFolders()](#getFontFolders--) | Gets font folders. |
| [clearCache()](#clearCache--) | Releases all custom fonts defined by user |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```

फ़ॉन्ट खोजने के लिए अतिरिक्त फ़ोल्डर जोड़ता है।

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // फ़ॉन्ट खोजने के लिए फ़ोल्डर
>  String[] folders = new String[] { dataDir };
>  // कस्टम फ़ॉन्ट निर्देशिका फ़ॉन्ट लोड करें
>  FontsLoader.loadExternalFonts(folders);
>  // कुछ काम करें और प्रस्तुतीकरण/स्लाइड्स रेंडरिंग करें
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // फ़ॉन्ट कैश साफ़ करें
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| directories | java.lang.String[] | अतिरिक्त फ़ॉन्ट पढ़ने के लिए निर्देशिकाएँ। |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

बाइनरी डेटा से फ़ॉन्ट जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | फ़ॉन्ट का डेटा |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

फ़ॉन्ट फ़ोल्डर प्राप्त करता है। उन फ़ोल्डरों को लौटाता है जो LoadExternalFonts मेथड से जोड़े गए हैं तथा सिस्टम फ़ॉन्ट फ़ोल्डर भी।

**रिटर्न मान:**  
java.lang.String[] - फ़ोल्डर नामों को शामिल करने वाला array

### clearCache() {#clearCache--}
```
public static void clearCache()
```

उपयोगकर्ता द्वारा परिभाषित सभी कस्टम फ़ॉन्ट जारी करता है।

--------------------

यह मेथड उपयोगकर्ता द्वारा परिभाषित कस्टम फ़ॉन्ट के साथ कैश को साफ़ करने की आवश्यकता रखता है।