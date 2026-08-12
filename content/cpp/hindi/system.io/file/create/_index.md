---
title: Create()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट बफ़र आकार और विकल्पों का उपयोग करके नई फ़ाइल बनाता है (या मौजूदा को अधिलेखित करता है) और इसे पढ़ने व लिखने की पहुँच के लिए खोलता है।
type: docs
weight: 53
url: /hi/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) विधि

नया फ़ाइल बनाता है (या मौजूदा को अधिलेखित करता है) और निर्दिष्ट बफ़र आकार और विकल्पों का उपयोग कर पढ़ने व लिखने की पहुँच के लिए खोलता है।

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | फ़ाइल बनाने या अधिलेखित करने के लिए पथ |
| bufferSize | **int32_t** | फ़ाइल को पढ़ते व लिखते समय बफ़र किए गए बाइट्स की संख्या |
| options | [FileOptions](../../fileoptions/) | फ़ाइल को बनाने या अधिलेखित करने का तरीका निर्दिष्ट करता है |

### वापसी मान

निर्दिष्ट फ़ाइल से जुड़े [FileStream](../../filestream/) ऑब्जेक्ट का एक साझा पॉइंटर

## संबंधित देखें

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)