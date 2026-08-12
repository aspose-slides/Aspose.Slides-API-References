---
title: Parse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष डबल-प्रेसिशन फ़्लोटिंग पॉइंट मान में परिवर्तित करता है।
type: docs
weight: 1
url: /hi/system/double/parse/
---
## Double::Parse(const String\&) विधि


निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, उसे समकक्ष डबल-प्रेसिशन फ़्लोटिंग पॉइंट मान में परिवर्तित करता है।

```cpp
static double System::Double::Parse(const String &value)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |

### वापसी मान

निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर डबल-प्रेसिशन फ़्लोटिंग पॉइंट मान।

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) विधि


निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, प्रदान किए गए फ़ॉर्मैटिंग जानकारी का उपयोग करके समकक्ष डबल-प्रेसिशन फ़्लोटिंग पॉइंट मान में परिवर्तित करता है।

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | स्ट्रिंग फ़ॉर्मेट जानकारी को समाहित करने वाले ऑब्जेक्ट का पॉइंटर। |

### वापसी मान

निर्दिष्ट स्ट्रिंग द्वारा दर्शाए हुए संख्या के बराबर डबल-प्रेसिशन फ़्लोटिंग पॉइंट मान।

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) विधि


```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि


```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) विधि


```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) विधि


निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, प्रदान किए गए फ़ॉर्मैटिंग जानकारी और नंबर शैली का उपयोग करके समकक्ष डबल-प्रेसिशन फ़्लोटिंग पॉइंट मान में परिवर्तित करता है।

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मूल्यों के बिटवाइज संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | स्ट्रिंग फ़ॉर्मेट जानकारी को समाहित करने वाले ऑब्जेक्ट का पॉइंटर। |

### वापसी मान

निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर डबल-प्रेसिशन फ़्लोटिंग पॉइंट मान।

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) विधि


```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि


```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) विधि


```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## देखें भी

* एन्यूम [NumberStyles](../../../system.globalization/numberstyles/)
* टाइपडेफ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* स्ट्रक्ट [Double](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)