---
title: TryParse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समतुल्य डबल-प्रेसिशन फ़्लोटिंग-पॉइंट मान में बदलता है।
type: docs
weight: 14
url: /hi/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) मेथड

निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समतुल्य डबल-प्रेसिजन फ़्लोटिंग-पॉइंट मान में बदलता है।

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिये स्ट्रिंग। |
| result | **double**\& | डबल-प्रेसिजन फ़्लोटिंग-पॉइंट वैरिएबल का रेफ़रेंस जहाँ रूपांतरण का परिणाम रखा जाता है। |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हुआ तो true, अन्यथा - false।

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) मेथड

निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को प्रदान किए गए फ़ॉर्मेटिंग जानकारी और नंबर स्टाइल का उपयोग करके समतुल्य डबल-प्रेसिजन फ़्लोटिंग-पॉइंट मान में बदलता है।

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिये स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमति देने वाले स्टाइल को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जो स्ट्रिंग फ़ॉर्मेट जानकारी रखता है। |
| result | **double**\& | डबल-प्रेसिजन फ़्लोटिंग-पॉइंट वैरिएबल का रेफ़रेंस जहाँ रूपांतरण का परिणाम रखा जाता है। |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हुआ तो true, अन्यथा - false।

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) मेथड

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) मेथड

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) मेथड

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## संबंधित देखें

* एनम [NumberStyles](../../../system.globalization/numberstyles/)
* टाइपडेफ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* स्ट्रक्ट [Double](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)