---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API संदर्भ
description: "जब डेरिव्ड क्लास में ओवरराइड किया जाता है, तो यह नाम और टेक्स्ट के बीच स्पेस के साथ प्रोसेसिंग इंस्ट्रक्शन लिखता है, जैसा कि निम्नलिखित है: <?name text?>."
type: docs
weight: 196
url: /hi/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) मेथड

When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | प्रोसेसिंग इंस्ट्रक्शन का नाम। |
| text | [String](../../../system/string/) | प्रोसेसिंग इंस्ट्रक्शन में शामिल करने के लिए पाठ। |
## टिप्पणी

This मेथड तब उपयोग किया जा रहा है जब [XmlWriter::WriteStartDocument](../writestartdocument/) पहले ही कॉल किया जा चुका है, एक XML घोषणा बनाने के लिये। 
## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlWriter](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)