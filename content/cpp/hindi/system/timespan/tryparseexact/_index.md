---
title: TryParseExact()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ॉर्मैट और फ़ॉर्मेट प्रदाता का उपयोग करके स्ट्रिंग को समकक्ष TimeSpan ऑब्जेक्ट में परिवर्तित करता है, और रूपांतरण का परिणाम लौटाता है।
type: docs
weight: 573
url: /hi/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) विधि


निर्दिष्ट फ़ॉर्मेट और फ़ॉर्मेट प्रोवाइडर का उपयोग करके स्ट्रिंग को समकक्ष [TimeSpan](../) ऑब्जेक्ट में परिवर्तित करता है, और परिवर्तन का परिणाम लौटाता है।

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | इनपुट स्ट्रिंग। |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | फ़ॉर्मेट स्ट्रिंग्स की [Array](../../array/)। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर जो संस्कृति-विशिष्ट फ़ॉर्मेटिंग जानकारी प्रदान करता है। |
| result | [TimeSpan](../)\& | स्ट्रिंग के अनुरूप समय अंतराल। |

### वापसी मान

यदि स्ट्रिंग सफलतापूर्वक परिवर्तित हो गई तो true; अन्यथा false।

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) विधि




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) विधि




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) विधि




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) विधि


निर्दिष्ट फ़ॉर्मेट, फ़ॉर्मेट प्रोवाइडर और स्टाइल्स का उपयोग करके स्ट्रिंग को समकक्ष [TimeSpan](../) ऑब्जेक्ट में परिवर्तित करता है, और परिवर्तन का परिणाम लौटाता है।

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | इनपुट स्ट्रिंग। |
| format | const [String](../../string/)\& | मानक या कस्टम फ़ॉर्मेट स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर जो संस्कृति-विशिष्ट फ़ॉर्मेटिंग जानकारी प्रदान करता है। |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | इनपुट स्ट्रिंग में मौजूद हो सकने वाले तत्वों को परिभाषित करता है। |
| result | [TimeSpan](../)\& | स्ट्रिंग के अनुरूप समय अंतराल। |

### वापसी मान

यदि स्ट्रिंग सफलतापूर्वक परिवर्तित हो गई तो true; अन्यथा false।

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) विधि




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) विधि 




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) विधि 




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) विधि


निर्दिष्ट फ़ॉर्मेट्स, फ़ॉर्मेट प्रोवाइडर और स्टाइल्स का उपयोग करके स्ट्रिंग को समकक्ष [TimeSpan](../) ऑब्जेक्ट में परिवर्तित करता है, और परिवर्तन का परिणाम लौटाता है।

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | इनपुट स्ट्रिंग। |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | फ़ॉर्मेट स्ट्रिंग्स की [Array](../../array/)। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर जो संस्कृति-विशिष्ट फ़ॉर्मेटिंग जानकारी प्रदान करता है। |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | इनपुट स्ट्रिंग में मौजूद हो सकने वाले तत्वों को परिभाषित करता है। |
| result | [TimeSpan](../)\& | स्ट्रिंग के अनुरूप समय अंतराल। |

### वापसी मान

यदि स्ट्रिंग सफलतापूर्वक परिवर्तित हो गई तो true; अन्यथा false।

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) विधि




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) विधि 




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) विधि 




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) विधि


निर्दिष्ट फ़ॉर्मेट और फ़ॉर्मेट प्रोवाइडर का उपयोग करके स्ट्रिंग को समकक्ष [TimeSpan](../) ऑब्जेक्ट में परिवर्तित करता है, और परिवर्तन का परिणाम लौटाता है।

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | इनपुट स्ट्रिंग। |
| format | const [String](../../string/)\& | मानक या कस्टम फ़ॉर्मेट स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर जो संस्कृति-विशिष्ट फ़ॉर्मेटिंग जानकारी प्रदान करता है। |
| result | [TimeSpan](../)\& | स्ट्रिंग के अनुरूप समय अंतराल। |

### वापसी मान

यदि स्ट्रिंग सफलतापूर्वक परिवर्तित हो गई तो true; अन्यथा false।

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) विधि 




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) विधि 




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) विधि 




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## संबंधित देखें

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [TimeSpan](../)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* नामस्थान [System](../../)
* Library [Aspose.Slides](../../../)