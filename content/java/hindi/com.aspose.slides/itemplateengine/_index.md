---
title: ITemplateEngine
second_title: Aspose.Slides for Java API संदर्भ
description: एक टेम्पलेट इंजन का प्रतिनिधित्व करता है जो टेम्पलेट और डेटा जोड़े को परिणामी आउटपुट (आमतौर पर HTML) में परिवर्तित करता है।
type: docs
url: /hi/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

एक टेम्पलेट इंजन का प्रतिनिधित्व करता है जो टेम्पलेट और डेटा जोड़े को परिणामी आउटपुट (आमतौर पर HTML) में परिवर्तित करता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | टेम्पलेट को टेम्पलेट संग्रह में जोड़ता है। |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | दिए गए कुंजी और मॉडल ऑब्जेक्ट के साथ टेम्पलेट को आउटपुट में परिवर्तित करता है। |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

टेम्पलेट को टेम्पलेट संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | टेम्पलेट संग्रह में टेम्पलेट के लिए कुंजी। |
| template | java.lang.String | टेम्पलेट की सामग्री। |
| modelType | com.aspose.ms.System.Type | टेम्पलेट के लिए मॉडल ऑब्जेक्ट का प्रकार। |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

दिए गए कुंजी और मॉडल ऑब्जेक्ट के साथ टेम्पलेट को आउटपुट में परिवर्तित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | टेम्पलेट संग्रह में टेम्पलेट के लिए कुंजी। |
| model | java.lang.Object | परिवर्तन के लिए डेटा वाला मॉडल ऑब्जेक्ट। |

**रिटर्न:**
java.lang.String - परिणामी आउटपुट एक स्ट्रिंग के रूप में।