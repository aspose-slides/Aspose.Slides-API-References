---
title: TryParse()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्ट्रिंग को समतुल्य TimeSpan ऑब्जेक्ट में परिवर्तित करता है और परिवर्तन का परिणाम लौटाता है।
type: docs
weight: 560
url: /hi/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) विधि

स्ट्रिंग को समतुल्य [TimeSpan](../) ऑब्जेक्ट में परिवर्तित करता है और परिवर्तन का परिणाम लौटाता है।

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | इनपुट स्ट्रिंग। |
| result | [TimeSpan](../)\& | स्ट्रिंग से संबंधित समय अंतराल। |

### रिटर्न वैल्यू

स्ट्रिंग सफलतापूर्वक परिवर्तित हुई तो true; अन्यथा false।

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) विधि

निर्दिष्ट फॉर्मेट प्रोवाइडर का उपयोग करके स्ट्रिंग को समतुल्य [TimeSpan](../) ऑब्जेक्ट में परिवर्तित करता है और परिवर्तन का परिणाम लौटाता है।

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | इनपुट स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी प्रदान करने वाला फ़ॉर्मेट प्रोवाइडर। |
| result | [TimeSpan](../)\& | स्ट्रिंग से संबंधित समय अंतराल। |

### रिटर्न वैल्यू

स्ट्रिंग सफलतापूर्वक परिवर्तित हुई तो true; अन्यथा false।

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) विधि




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) विधि




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) विधि




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## देखें

* टाइपडिफ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [TimeSpan](../)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)