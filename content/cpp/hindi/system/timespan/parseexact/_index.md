---
title: ParseExact()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ॉर्मेट्स, फ़ॉर्मेट प्रोवाइडर और स्टाइल्स का उपयोग करके स्ट्रिंग को समकक्ष TimeSpan ऑब्जेक्ट में बदलता है।
type: docs
weight: 547
url: /hi/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) मेथड


Converts string to equivalent [TimeSpan](../) object using the specified formats, format provider and styles.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) फ़ॉर्मेट स्ट्रिंग्स का |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider that supplies culture-specific formatting information. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Defines elements that may be present in input string. |

### रिटर्न वैल्यू

Time interval that corresponds to string.

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) मेथड




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) मेथड




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) मेथड




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) मेथड


Converts string to equivalent [TimeSpan](../) object using the specified format, format provider and styles.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |
| format | const [String](../../string/)\& | Standard or custom format string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider that supplies culture-specific formatting information. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Defines elements that may be present in input string. |

### रिटर्न वैल्यू

Time interval that corresponds to string.

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) मेथड




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) मेथड




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) मेथड




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## देखें

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)