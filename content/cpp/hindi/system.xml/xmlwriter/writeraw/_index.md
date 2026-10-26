---
title: WriteRaw()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: जब एक व्युत्पन्न वर्ग में अधिलेखित किया जाता है, तो यह एक कैरेक्टर बफ़र से कच्चा मार्कअप मैन्युअल रूप से लिखता है।
type: docs
weight: 287
url: /hi/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) विधि

जब एक व्युत्पन्न वर्ग में अधिलेखित किया जाता है, तो यह एक कैरेक्टर बफ़र से कच्चा मार्कअप मैन्युअल रूप से लिखता है।

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | लिखने के लिये पाठ युक्त कैरेक्टर एरे। |
| index | **int32_t** | बफ़र में लिखने वाले पाठ की शुरुआत के स्थान को दर्शाता है। |
| count | **int32_t** | लिखने हेतु कैरेक्टरों की संख्या। |

## XmlWriter::WriteRaw(const String\&) विधि

जब एक व्युत्पन्न वर्ग में अधिलेखित किया जाता है, तो यह एक स्ट्रिंग से कच्चा मार्कअप मैन्युअल रूप से लिखता है।

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) जिसमें लिखने के लिये पाठ हो। |

## सम्बंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlWriter](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml](../../)
* Library [Aspose.Slides](../../../)