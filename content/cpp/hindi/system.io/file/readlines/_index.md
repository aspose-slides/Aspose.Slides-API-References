---
title: ReadLines()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट टेक्स्ट फ़ाइल की सामग्री को लाइन दर लाइन पढ़ता है, निर्दिष्ट कैरेक्टर एन्कोडिंग का उपयोग करता है और स्ट्रिंग्स का इटेरेबल संग्रह लौटाता है, जिसमें प्रत्येक फ़ाइल की सामग्री की एक लाइन दर्शाता है।
type: docs
weight: 326
url: /hi/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) विधि

फ़ाइल की निर्दिष्ट टेक्स्ट सामग्री को लाइन-दर-लाइन पढ़ता है, निर्दिष्ट कैरेक्टर एन्कोडिंग का उपयोग करता है और स्ट्रिंग की इटेरेबल संग्रह लौटाता है, जिसमें से प्रत्येक फ़ाइल की सामग्री की एक लाइन दर्शाता है।

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | फ़ाइल को पढ़ने का पथ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए वर्ण एन्कोडिंग |

### रिटर्न वैल्यू

निर्दिष्ट फ़ाइल की सामग्री का प्रतिनिधित्व करने वाले स्ट्रिंग्स का एक इटेरेबल कलेक्शन

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)