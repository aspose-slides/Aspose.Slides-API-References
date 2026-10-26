---
title: WriteState
second_title: Aspose.Slides for C++ API संदर्भ
description: XmlWriter की स्थिति निर्दिष्ट करता है।
type: docs
weight: 755
url: /hi/system.xml/writestate/
---
## WriteState enum

[XmlWriter](../xmlwriter/) की स्थिति निर्दिष्ट करता है।

```cpp
enum class WriteState
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Start | 0 | इसे दर्शाता है कि XmlWriter::Write मेथड अभी तक नहीं बुलाया गया है। |
| Prolog | 1 | इसे दर्शाता है कि प्रोलॉग लिखा जा रहा है। |
| Element | 2 | इसे दर्शाता है कि एक तत्व की प्रारंभ टैग लिखा जा रहा है। |
| Attribute | 3 | इसे दर्शाता है कि एक विशेषता मान लिखा जा रहा है। |
| Content | 4 | इसे दर्शाता है कि तत्व की सामग्री लिखा जा रहा है। |
| Closed | 5 | इसे दर्शाता है कि [XmlWriter::Close](../xmlwriter/close/) मेथड को कॉल किया गया है। |
| Error | 6 | एक अपवाद फेंका गया है, जिससे [XmlWriter](../xmlwriter/) एक अमान्य स्थिति में रह गया है। आप [XmlWriter::Close](../xmlwriter/close/) मेथड को कॉल करके [XmlWriter](../xmlwriter/) को [WriteState::Closed](./) स्थिति में रख सकते हैं। किसी भी अन्य [XmlWriter](../xmlwriter/) मेथड कॉल से InvalidOperationException उत्पन्न होगा। |

## देखें

* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)