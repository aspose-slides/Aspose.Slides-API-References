---
title: BinaryWriter()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट एन्कोडिंग का उपयोग करके निर्दिष्ट स्ट्रीम पर डेटा लिखने वाली BinaryWriter क्लास की एक इंस्टेंस बनाता है।
type: docs
weight: 1
url: /hi/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) निर्माता


निर्दिष्ट एन्कोडिंग का उपयोग करके निर्दिष्ट स्ट्रीम पर डेटा लिखने वाली [BinaryWriter](../) क्लास की एक इंस्टेंस बनाता है।

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | आउटपुट स्ट्रीम |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए एन्कोडिंग |
| leaveopen | **bool** | निर्दिष्ट करता है कि क्या स्ट्रीम **stream** को वर्तमान ऑब्जेक्ट नष्ट होने के बाद (true) खुला छोड़ना चाहिए या नहीं (false) |

## संबंधित

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)