---
title: TryParse()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट स्ट्रिंग को DateTimeOffset ऑब्जेक्ट में परिवर्तित करने का प्रयास करता है।
type: docs
weight: 729
url: /hi/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) विधि

निर्दिष्ट स्ट्रिंग को [DateTimeOffset](../) ऑब्जेक्ट में बदलने का प्रयास करता है।

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) को बदलने के लिए |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) जो **input** के बराबर है। |

### रिटर्न वैल्यू

यदि **input** सफलतापूर्वक बदला गया हो तो true, अन्यथा false।

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) विधि

निर्दिष्ट स्ट्रिंग को निर्दिष्ट फॉर्मेट प्रोवाइडर और फॉर्मेटिंग स्टाइल का उपयोग करके [DateTimeOffset](../) ऑब्जेक्ट में बदलने का प्रयास करता है।

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) को बदलने के लिए |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | दिनांक और समय फ़ॉर्मेटिंग स्टाइल्स। |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) जो **input** के बराबर है। |

### रिटर्न वैल्यू

यदि **input** सफलतापूर्वक बदला गया हो तो true, अन्यथा false।

## देखें

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)