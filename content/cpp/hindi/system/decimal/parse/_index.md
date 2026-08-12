---
title: Parse()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक दशमलव संख्या के स्ट्रिंग प्रतिनिधित्व को Decimal वर्ग की समतुल्य इंस्टेंस में परिवर्तित करता है।
type: docs
weight: 469
url: /hi/system/decimal/parse/
---
## Decimal::Parse(const String\&) विधि

एक दशमलव संख्या का स्ट्रिंग प्रतिनिधित्व [Decimal](../) क्लास की समान इंस्टेंस में परिवर्तित करता है।

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | एक संख्या का स्ट्रिंग प्रतिनिधित्व |

### वापसी मान

एक नया [Decimal](../) क्लास का इंस्टेंस जो निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए मान के बराबर होता है।

## Decimal::Parse(const String\&, Globalization::NumberStyles) विधि

निर्दिष्ट शैली का उपयोग करके दशमलव संख्या का स्ट्रिंग प्रतिनिधित्व [Decimal](../) क्लास की समान इंस्टेंस में परिवर्तित करता है।

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | परिवर्तित करने के लिए दशमलव मान का स्ट्रिंग प्रतिनिधित्व |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | एक बिटवाइज़ संयोजन **s** के बारे में अतिरिक्त जानकारी, **s** में उपस्थित शैली तत्वों के बारे में, या **s** से एक [Decimal](../) ऑब्जेक्ट में रूपांतरण के बारे में प्रदान करता है |

### वापसी मान

एक नया [Decimal](../) क्लास का इंस्टेंस जो निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए मान के बराबर होता है

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) विधि

निर्दिष्ट फ़ॉर्मेट प्रदाता का उपयोग करके दशमलव संख्या का स्ट्रिंग प्रतिनिधित्व [Decimal](../) क्लास की समान इंस्टेंस में परिवर्तित करता है।

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | परिवर्तित करने के लिए दशमलव मान का स्ट्रिंग प्रतिनिधित्व |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रदाता |

### वापसी मान

एक नया [Decimal](../) क्लास का इंस्टेंस जो निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए मान के बराबर होता है

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) विधि

निर्दिष्ट शैली और फ़ॉर्मेट प्रदाता का उपयोग करके दशमलव संख्या का स्ट्रिंग प्रतिनिधित्व [Decimal](../) क्लास की समान इंस्टेंस में परिवर्तित करता है।

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | परिवर्तित करने के लिए दशमलव मान का स्ट्रिंग प्रतिनिधित्व |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | एक बिटवाइज़ संयोजन **s** के बारे में अतिरिक्त जानकारी, **s** में उपस्थित शैली तत्वों के बारे में, या **s** से एक [Decimal](../) ऑब्जेक्ट में रूपांतरण के बारे में प्रदान करता है |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रदाता |

### वापसी मान

एक नया [Decimal](../) क्लास का इंस्टेंस जो निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए मान के बराबर होता है

## देखें

* एनम [NumberStyles](../../../system.globalization/numberstyles/)
* टाइपडेफ [SharedPtr](../../sharedptr/)
* क्लास [Decimal](../)
* क्लास [String](../../string/)
* क्लास [IFormatProvider](../../iformatprovider/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)