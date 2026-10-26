---
title: Parse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग प्रतिनिधित्व को तिथि और समय मान में बदलकर उसे समान DateTime ऑब्जेक्ट में परिवर्तित करता है।
type: docs
weight: 859
url: /hi/system/datetime/parse/
---
## DateTime::Parse(const String\&) मेथड


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | कनवर्ट करने के लिए तिथि और समय मान का स्ट्रिंग प्रतिनिधित्व। |

### रिटर्न वैल्यू

A new instance of [DateTime](../) class that represents the date and time value equivalent to that represented by the specified string.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) मेथड


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object using culture-specific format information.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | कनवर्ट करने के लिए तिथि और समय मान का स्ट्रिंग प्रतिनिधित्व। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) ऑब्जेक्ट जो संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी प्रदान करता है। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | एक बिटवाइज़ संयोजन जिसमें enumeration मान होते हैं जो **s** के बारे में अतिरिक्त जानकारी, **s** में मौजूद हो सकने वाले स्टाइल एलिमेंट्स के बारे में, या **s** से एक [DateTime](../) ऑब्जेक्ट में परिवर्तन के बारे में प्रदान करता है। |

### रिटर्न वैल्यू

A new instance of [DateTime](../) class that represents the date and time value equivalent to that represented by the specified string.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) मेथड




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) मेथड




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) मेथड




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## संबंधित देखें

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)