---
title: TryParse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 8-बिट अनसाइनड इंटीजर में बदलता है।
type: docs
weight: 14
url: /hi/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) विधि


निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 8-बिट अनसाइनड इंटीजर में बदलता है।

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिये स्ट्रिंग। |
| result | **uint8_t**\& | वह 8-बिट अनसाइनड इंटीजर वेरिएबल जिसका रेफ़रेंस रूपांतरण के परिणाम को रखता है। |

### वापसी मान

रूपांतरण सफल होने पर True, अन्यथा - false।

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) विधि


निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व है, को प्रदान की गई फ़ॉर्मेटिंग जानकारी और नंबर स्टाइल का उपयोग करके समकक्ष 8-बिट अनसाइनड इंटीजर में बदलता है।

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिये स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles एनम के मानों का बिटवाइज़ संयोजन, जो संख्या के स्ट्रिंग प्रतिनिधित्व के अनुमत स्टाइल को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | वह ऑब्जेक्ट जिसका पॉइंटर स्ट्रिंग फ़ॉर्मेट जानकारी रखता है। |
| result | **uint8_t**\& | वह 8-बिट अनसाइनड इंटीजर वेरिएबल जिसका रेफ़रेंस रूपांतरण के परिणाम को रखता है। |

### वापसी मान

रूपांतरण सफल होने पर True, अन्यथा - false।

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) विधि




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) विधि




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) विधि




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## संदर्भ

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)