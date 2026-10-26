---
title: FontsLoader
second_title: Aspose.Slides के लिए Java API संदर्भ
description: उपयोगकर्ता द्वारा परिभाषित कस्टम फ़ॉन्ट्स को लोड करने के लिए क्लास।
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

उपयोगकर्ता द्वारा परिभाषित कस्टम फ़ॉन्ट्स को लोड करने के लिए क्लास। इसे किसी भी प्रस्तुति ऑब्जेक्ट को बनाने से पहले उपयोग किया जाना चाहिए।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | फ़ॉन्ट खोजने के लिए अतिरिक्त फ़ोल्डर जोड़ता है। |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | बाइनरी डेटा से फ़ॉन्ट जोड़ता है। |
| [getFontFolders()](#getFontFolders--) | फ़ॉन्ट फ़ोल्डर प्राप्त करता है। |
| [clearCache()](#clearCache--) | उपयोगकर्ता द्वारा परिभाषित सभी कस्टम फ़ॉन्ट्स को रिलीज़ करता है। |

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
>  // कस्टम फ़ॉन्ट डायरेक्टरी फ़ॉन्ट को लोड करें
>  FontsLoader.loadExternalFonts(folders);
>  // कुछ कार्य करें और प्रस्तुति/स्लाइड रेंडरिंग करें
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

फ़ॉन्ट फ़ोल्डर प्राप्त करता है। वह फ़ोल्डर लौटाता है जो LoadExternalFonts विधि द्वारा जोड़े गए हैं और सिस्टम फ़ॉन्ट फ़ोल्डर भी।

**रिटर्न:**
java.lang.String[] - फ़ोल्डर नामों वाला एरे

### clearCache() {#clearCache--}
```
public static void clearCache()
```

उपयोगकर्ता द्वारा परिभाषित सभी कस्टम फ़ॉन्ट्स को रिलीज़ करता है।

--------------------

इस विधि को उपयोगकर्ता द्वारा परिभाषित कस्टम फ़ॉन्ट्स के साथ कैश साफ़ करने की आवश्यकता है।