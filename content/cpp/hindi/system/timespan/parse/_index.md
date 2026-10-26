---
title: Parse()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रिंग को समकक्ष TimeSpan ऑब्जेक्ट में परिवर्तित करता है।
type: docs
weight: 534
url: /hi/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) method

स्ट्रिंग को समकक्ष [TimeSpan](../) ऑब्जेक्ट में परिवर्तित करता है।

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | इनपुट स्ट्रिंग। |

### रिटर्न वैल्यू

स्ट्रिंग से मेल खाता समय अंतराल।

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

निर्दिष्ट फ़ॉर्मेट प्रोवाइडर का उपयोग करके स्ट्रिंग को समकक्ष [TimeSpan](../) ऑब्जेक्ट में परिवर्तित करता है।

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | इनपुट स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर जो सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी प्रदान करता है। |

### रिटर्न वैल्यू

स्ट्रिंग से मेल खाता समय अंतराल।

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## देखें

* टाइपडिफ [SharedPtr](../../sharedptr/)
* क्लास [TimeSpan](../)
* क्लास [String](../../string/)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)