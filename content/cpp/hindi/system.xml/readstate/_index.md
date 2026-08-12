---
title: ReadState
second_title: Aspose.Slides for C++ API संदर्भ
description: रीडर की स्थिति को निर्दिष्ट करता है।
type: docs
weight: 703
url: /hi/system.xml/readstate/
---
## ReadState enum

रीडर की स्थिति को निर्दिष्ट करता है।

```cpp
enum class ReadState
```

### Values

| नाम | मान | विवरण |
| --- | --- | --- |
| Initial | 0 | The [XmlReader::Read](../xmlreader/read/) मेथड को कॉल नहीं किया गया है। |
| Interactive | 1 | The [XmlReader::Read](../xmlreader/read/) मेथड को कॉल किया गया है। रीडर पर अतिरिक्त मेथड्स को कॉल किया जा सकता है। |
| Error | 2 | एक त्रुटि हुई है जो पढ़ने के कार्य को जारी रखने से रोकती है। |
| EndOfFile | 3 | फ़ाइल के अंत तक सफलतापूर्वक पहुँच गया है। |
| Closed | 4 | The [XmlReader::Close](../xmlreader/close/) मेथड को कॉल किया गया है। |

## संबंधित देखें

* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)