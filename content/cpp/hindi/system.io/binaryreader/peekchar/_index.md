---
title: PeekChar()
second_title: Aspose.Slides for C++ API संदर्भ
description: इनपुट स्ट्रीम से एकल अक्षर पढ़ता है बिना स्ट्रीम के रीड कर्सर को बदले।
type: docs
weight: 53
url: /hi/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() मेथड

बिना स्ट्रीम के रीड कर्सर को बदले, इनपुट स्ट्रीम से एक एकल अक्षर पढ़ता है।

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### रिटर्न वैल्यू

पढ़ा गया अक्षर UTF-16 एन्कोडिंग में एन्कोड किया गया है; यदि पढ़ा गया अक्षर UTF-16 एन्कोडिंग में दो कोडपॉइंट्स द्वारा दर्शाया जाता है तो केवल उच्च surragate लौटाया जाता है; यदि कोई अक्षर नहीं पढ़ा गया तो -1 लौटाया जाता है।

## संबंधित देखें

* क्लास [BinaryReader](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)