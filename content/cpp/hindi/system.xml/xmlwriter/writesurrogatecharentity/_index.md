---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो यह सरोगेट कैरेक्टर जोड़ी के लिए सरोगेट कैरेक्टर एंटिटी बनाता और लिखता है।
type: docs
weight: 261
url: /hi/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) विधि

जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो यह सरोगेट कैरेक्टर जोड़ी के लिए सरोगेट कैरेक्टर एंटिटी बनाता है और लिखता है।

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lowChar | char16_t | लो सरोगेट। यह मान 0xDC00 और 0xDFFF के बीच होना चाहिए। |
| highChar | char16_t | हाई सरोगेट। यह मान 0xD800 और 0xDBFF के बीच होना चाहिए। |

## देखें

* क्लास [XmlWriter](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)