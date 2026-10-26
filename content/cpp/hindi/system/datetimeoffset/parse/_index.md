---
title: Parse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग को DateTimeOffset के समकक्ष में परिवर्तित करता है।
type: docs
weight: 703
url: /hi/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) मेथड

निर्दिष्ट स्ट्रिंग को [DateTimeOffset](../) के समकक्ष में परिवर्तित करता है।

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) को परिवर्तित करने के लिए। |

### रिटर्न वैल्यू

[DateTimeOffset](../) जो **input** के बराबर है।

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) मेथड

निर्दिष्ट स्ट्रिंग को [DateTimeOffset](../) ऑब्जेक्ट में परिवर्तित करता है, निर्दिष्ट फ़ॉर्मेट प्रोवाइडर और फ़ॉर्मेटिंग शैली का उपयोग करके।

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) को परिवर्तित करने के लिए। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | तारीख और समय फ़ॉर्मेटिंग शैलियाँ। |

### रिटर्न वैल्यू

[DateTimeOffset](../) जो **input** के बराबर है।

## संबंधित देखें

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)