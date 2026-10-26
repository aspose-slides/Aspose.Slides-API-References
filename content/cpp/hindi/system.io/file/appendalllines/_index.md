---
title: AppendAllLines()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग संग्रह से स्ट्रिंग्स को निर्दिष्ट फ़ाइल में निर्दिष्ट एन्कोडिंग का उपयोग करके प्रत्येक स्ट्रिंग को नई पंक्ति में लिखकर जोड़ता है। यदि निर्दिष्ट फ़ाइल मौजूद नहीं है, तो इसे बनाया जाता है। सभी स्ट्रिंग्स लिखने के बाद फ़ाइल बंद कर दी जाती है।
type: docs
weight: 1
url: /hi/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) विधि

निर्दिष्ट स्ट्रिंग संग्रह से स्ट्रिंग्स को निर्दिष्ट फ़ाइल में निर्दिष्ट एन्कोडिंग का उपयोग करके प्रत्येक स्ट्रिंग को नई पंक्ति में लिखकर जोड़ता है। यदि निर्दिष्ट फ़ाइल मौजूद नहीं है, तो इसे बनाया जाता है। सभी स्ट्रिंग्स लिखने के बाद फ़ाइल बंद कर दी जाती है।

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | स्ट्रिंग्स जोड़ने वाली फ़ाइल का पथ |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | फ़ाइल में लिखने वाली स्ट्रिंग्स |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए अक्षर एन्कोडिंग |

## अन्य देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* क्लास [String](../../../system/string/)
* क्लास [IEnumerable](../../../system.collections.generic/ienumerable/)
* क्लास [File](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)