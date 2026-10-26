---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: एक टेम्प्लेट इंजन का प्रतिनिधित्व करता है जो टेम्प्लेट और डेटा जोड़े को परिणामी आउटपुट में बदलता है, आमतौर पर HTML।
type: docs
url: /hi/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

एक टेम्प्लेट इंजन का प्रतिनिधित्व करता है जो टेम्प्लेट और डेटा जोड़े को परिणामी आउटपुट (आमतौर पर HTML) में बदलता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | टेम्प्लेट को टेम्प्लेट संग्रह में जोड़ता है। |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | दिए गए कुंजी और मॉडल ऑब्जेक्ट के साथ टेम्प्लेट को आउटपुट में बदलता है। |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


टेम्प्लेट को टेम्प्लेट संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | टेम्प्लेट संग्रह में टेम्प्लेट के लिये कुंजी। |
| template | java.lang.String | टेम्प्लेट सामग्री। |
| modelType | com.aspose.ms.System.Type | टेम्प्लेट के लिये मॉडल ऑब्जेक्ट का प्रकार। |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


दिए गए कुंजी और मॉडल ऑब्जेक्ट के साथ टेम्प्लेट को आउटपुट में बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | टेम्प्लेट संग्रह में टेम्प्लेट के लिये कुंजी। |
| model | java.lang.Object | रूपांतरण के लिए डेटा के साथ मॉडल ऑब्जेक्ट। |

**रिटर्न:**
java.lang.String - परिणामी आउटपुट एक स्ट्रिंग के रूप में।