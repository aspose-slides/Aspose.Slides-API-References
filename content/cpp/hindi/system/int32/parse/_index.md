---
title: Parse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग जो किसी संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, को समतुल्य 32-बिट साइन्ड इंटीजर में परिवर्तित करता है।
type: docs
weight: 1
url: /hi/system/int32/parse/
---
## Int32::Parse(const String\&) विधि

निर्दिष्ट स्ट्रिंग जो किसी संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, को समतुल्य 32-बिट साइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static int32_t System::Int32::Parse(const String &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |

### वापसी मान

निर्दिष्ट स्ट्रिंग द्वारा प्रदर्शित संख्या के बराबर 32-बिट साइन्ड इंटीजर।

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) विधि

प्रदान किए गए फॉर्मेटिंग जानकारी का उपयोग कर, निर्दिष्ट स्ट्रिंग जो किसी संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, को समतुल्य 32-बिट साइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | स्ट्रिंग फॉर्मेट जानकारी को समाहित करने वाले ऑब्जेक्ट का एक पॉइंटर। |

### वापसी मान

निर्दिष्ट स्ट्रिंग द्वारा प्रदर्शित संख्या के बराबर 32-बिट साइन्ड इंटीजर।

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) विधि




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) विधि




```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) विधि

प्रदान किए गए फॉर्मेटिंग जानकारी और नंबर शैली का उपयोग कर, निर्दिष्ट स्ट्रिंग जो किसी संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, को समतुल्य 32-बिट साइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमति योग्य शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | स्ट्रिंग फॉर्मेट जानकारी को समाहित करने वाले ऑब्जेक्ट का एक पॉइंटर। |

### वापसी मान

निर्दिष्ट स्ट्रिंग द्वारा प्रदर्शित संख्या के बराबर 32-बिट साइन्ड इंटीजर।

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) विधि




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) विधि




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) विधि




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) विधि




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) विधि




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## संबंधित देखें

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int32](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [ReadOnlySpan](../../readonlyspan/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)