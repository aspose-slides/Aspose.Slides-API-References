---
title: TryParseExact()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ॉर्मैट, फ़ॉर्मैट प्रोवाइडर और फ़ॉर्मैटिंग स्टाइल का उपयोग करके निर्दिष्ट स्ट्रिंग को DateTimeOffset ऑब्जेक्ट में परिवर्तित करने का प्रयास करता है।
type: docs
weight: 742
url: /hi/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) विधि

निर्दिष्ट स्ट्रिंग को [DateTimeOffset](../) ऑब्जेक्ट में परिवर्तित करने का प्रयास करता है, निर्दिष्ट फ़ॉर्मैट, फ़ॉर्मैट प्रोवाइडर और फ़ॉर्मैटिंग स्टाइल का उपयोग करके।

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) को परिवर्तित करने के लिए। |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | फ़ॉर्मेट स्ट्रिंग्स की सरणियां। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | तारीख और समय के फ़ॉर्मेटिंग स्टाइल्स। |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) जो **input** के बराबर है। |

### रिटर्न वैल्यू

true यदि **input** सफलतापूर्वक परिवर्तित हो गया, अन्यथा - false।

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) विधि

निर्दिष्ट स्ट्रिंग को [DateTimeOffset](../) ऑब्जेक्ट में परिवर्तित करने का प्रयास करता है, निर्दिष्ट फ़ॉर्मेट, फ़ॉर्मेट प्रोवाइडर और फ़ॉर्मेटिंग स्टाइल का उपयोग करके।

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) को परिवर्तित करने के लिए। |
| format | const [String](../../string/)\& | फ़ॉर्मेट स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | तारीख और समय के फ़ॉर्मेटिंग स्टाइल्स। |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) जो **input** के बराबर है। |

### रिटर्न वैल्यू

true यदि **input** सफलतापूर्वक परिवर्तित हो गया, अन्यथा - false।

## संबंधित देखें

* एनम [DateTimeStyles](../../../system.globalization/datetimestyles/)
* टाइपडिफ [ArrayPtr](../../arrayptr/)
* टाइपडिफ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [DateTimeOffset](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)