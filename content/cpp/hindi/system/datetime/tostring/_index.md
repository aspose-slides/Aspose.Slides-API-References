---
title: ToString()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए तिथि और समय मान का स्ट्रिंग प्रतिनिधित्व लौटाता है, जो वर्तमान संस्कृति द्वारा परिभाषित फ़ॉर्मेटिंग नियमों का उपयोग करता है।
type: docs
weight: 482
url: /hi/system/datetime/tostring/
---
## DateTime::ToString() const मेथड

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए तिथि और समय मान का स्ट्रिंग प्रतिनिधित्व लौटाता है, जो वर्तमान संस्कृति द्वारा परिभाषित फ़ॉर्मेटिंग कन्वेंशन का उपयोग करता है।

```cpp
String System::DateTime::ToString() const
```

### रिटर्न वैल्यू

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान का स्ट्रिंग प्रतिनिधित्व

## DateTime::ToString(const String\&) const मेथड

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए तिथि और समय मान का स्ट्रिंग प्रतिनिधित्व लौटाता है, जो निर्दिष्ट फ़ॉर्मेट और वर्तमान संस्कृति द्वारा परिभाषित फ़ॉर्मेटिंग कन्वेंशन का उपयोग करता है।

```cpp
String System::DateTime::ToString(const String &format) const
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | const [String](../../string/)\& | एक फ़ॉर्मेट स्ट्रिंग |

### रिटर्न वैल्यू

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान का स्ट्रिंग प्रतिनिधित्व, जो **format** द्वारा परिभाषित फ़ॉर्मेट और वर्तमान संस्कृति के अनुसार स्वरूपित किया गया है।

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const मेथड

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए तिथि और समय मान का स्ट्रिंग प्रतिनिधित्व लौटाता है, जो निर्दिष्ट फ़ॉर्मेट जानकारी का उपयोग करता है।

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट जानकारी को दर्शाने वाला एक ऑब्जेक्ट |

### रिटर्न वैल्यू

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान का स्ट्रिंग प्रतिनिधित्व, जो **formatProvider** द्वारा प्रदत्त फ़ॉर्मेट जानकारी के अनुसार स्वरूपित किया गया है।

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const मेथड




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const मेथड




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const मेथड




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const मेथड

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए तिथि और समय मान का स्ट्रिंग प्रतिनिधित्व लौटाता है, जो निर्दिष्ट फ़ॉर्मेट जानकारी का उपयोग करता है।

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | const [String](../../string/)\& | एक फ़ॉर्मेट स्ट्रिंग |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट जानकारी को दर्शाने वाला एक ऑब्जेक्ट |

### रिटर्न वैल्यू

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान का स्ट्रिंग प्रतिनिधित्व, जो **provider** द्वारा प्रदत्त फ़ॉर्मेट जानकारी और फ़ॉर्मेट स्ट्रिंग **format** के अनुसार स्वरूपित किया गया है।

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const मेथड




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const मेथड




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const मेथड




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## संबंधित देखें

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [DateTime](../)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)