---
title: ParseExact()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ॉर्मेट, फ़ॉर्मेट प्रोवाइडर और फ़ॉर्मेटिंग शैली का उपयोग करके निर्दिष्ट स्ट्रिंग को DateTimeOffset ऑब्जेक्ट में परिवर्तित करता है।
type: docs
weight: 716
url: /hi/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method

निर्दिष्ट स्ट्रिंग को निर्दिष्ट फ़ॉर्मेट, फ़ॉर्मेट प्रोवाइडर और फ़ॉर्मेटिंग शैली का उपयोग करके [DateTimeOffset](../) ऑब्जेक्ट में परिवर्तित करता है।

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) को परिवर्तित करने के लिए। |
| format | const [String](../../string/)\& | फ़ॉर्मेट स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | तारीख और समय फ़ॉर्मेटिंग शैलियाँ। |

### रिटर्न वैल्यू

[DateTimeOffset](../) जो **input** के बराबर है।

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method

निर्दिष्ट स्ट्रिंग को निर्दिष्ट फ़ॉर्मेट्स, फ़ॉर्मेट प्रोवाइडर और फ़ॉर्मेटिंग शैली का उपयोग करके [DateTimeOffset](../) ऑब्जेक्ट में परिवर्तित करता है।

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) को परिवर्तित करने के लिए। |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | फ़ॉर्मेट स्ट्रिंग्स का [Array](../../array/)। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | तारीख और समय फ़ॉर्मेटिंग शैलियाँ। |

### रिटर्न वैल्यू

[DateTimeOffset](../) जो **input** के बराबर है।

## संबंधित देखें

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)