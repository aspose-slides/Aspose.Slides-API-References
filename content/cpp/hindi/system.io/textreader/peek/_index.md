---
title: Peek()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रीम से एक एकल अक्षर को पढ़ता है बिना स्ट्रीम के रीड कर्सर को बदले।
type: docs
weight: 27
url: /hi/system.io/textreader/peek/
---
## TextReader::Peek() मेथड

स्ट्रीम से एक एकल वर्ण पढ़ता है बिना स्ट्रीम के रीड कर्सर को बदले।

```cpp
virtual int System::IO::TextReader::Peek()
```

### रिटर्न वैल्यू

UTF-16 एन्कोडिंग के साथ एन्कोड किया गया पढ़ा गया वर्ण; यदि पढ़ा गया वर्ण UTF-16 एन्कोडिंग में दो कोडपॉइंट्स द्वारा प्रतिनिधित्व किया गया है तो केवल high surrogate लौटाया जाता है; यदि कोई वर्ण नहीं पढ़ा गया तो -1 लौटाया जाता है

## देखें

* क्लास [TextReader](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)