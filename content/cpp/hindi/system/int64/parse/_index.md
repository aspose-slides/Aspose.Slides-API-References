---
title: Parse()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, उसे समकक्ष 64-बिट साइन्ड इंटीजर में परिवर्तित करता है।
type: docs
weight: 1
url: /hi/system/int64/parse/
---
## Int64::Parse(const String\&) मेथड


निर्दिष्ट स्ट्रिंग जो किसी संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, उसे समकक्ष 64-बिट साइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static int64_t System::Int64::Parse(const String &value)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | कनवर्ट करने के लिए स्ट्रिंग। |

### रिटर्न मान

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 64-बिट साइन्ड इंटीजर।

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) मेथड


निर्दिष्ट स्ट्रिंग जो किसी संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, उसे प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके समकक्ष 64-बिट साइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | कनवर्ट करने के लिए स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक पॉइंटर जो उस ऑब्जेक्ट की ओर इशारा करता है जिसमें स्ट्रिंग फ़ॉर्मेट जानकारी होती है। |

### रिटर्न मान

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 64-बिट साइन्ड इंटीजर।

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) मेथड




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) मेथड




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) मेथड




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) मेथड


निर्दिष्ट स्ट्रिंग जो किसी संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, उसे प्रदान की गई फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके समकक्ष 64-बिट साइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | कनवर्ट करने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles एनीम के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक पॉइंटर जो उस ऑब्जेक्ट की ओर इशारा करता है जिसमें स्ट्रिंग फ़ॉर्मेट जानकारी होती है। |

### रिटर्न मान

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 64-बिट साइन्ड इंटीजर।

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) मेथड




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) मेथड




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) मेथड




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## देखें

* एन्युम [NumberStyles](../../../system.globalization/numberstyles/)
* टाइपडैफ़ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [Int64](../)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)