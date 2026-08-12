---
title: TryParse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समतुल्य 64-बिट अनसाइन्ड इंटीजर में परिवर्तित करता है।
type: docs
weight: 14
url: /hi/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) विधि


निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समतुल्य 64-बिट अनसाइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने वाली स्ट्रिंग। |
| result | **uint64_t**\& | परिवर्तन का परिणाम जहाँ रखा जाता है, उस 64-बिट अनसाइन्ड इंटीजर वेरिएबल का रेफ़रेंस। |

### Return Value

यदि परिवर्तन सफल हुआ तो true, अन्यथा false।

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) विधि


निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को प्रदान किए गए फ़ॉर्मेटिंग जानकारी और नंबर शैली का उपयोग करके समतुल्य 64-बिट अनसाइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने वाली स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles एन्यूम के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जिसमें स्ट्रिंग फ़ॉर्मेट जानकारी होती है। |
| result | **uint64_t**\& | परिवर्तन का परिणाम जहाँ रखा जाता है, उस 64-बिट अनसाइन्ड इंटीजर वेरिएबल का रेफ़रेंस। |

### Return Value

यदि परिवर्तन सफल हुआ तो true, अन्यथा false।

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) विधि




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) विधि




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) विधि




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)