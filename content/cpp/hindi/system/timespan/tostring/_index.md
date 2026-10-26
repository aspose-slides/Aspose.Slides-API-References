---
title: ToString()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए समय अंतराल का स्ट्रिंग प्रतिनिधित्व लौटाता है।
type: docs
weight: 261
url: /hi/system/timespan/tostring/
---
## TimeSpan::ToString() const method

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए समय अंतराल का स्ट्रिंग प्रतिनिधित्व लौटाता है।

```cpp
String System::TimeSpan::ToString() const
```
## TimeSpan::ToString(const String\&) const method

निर्दिष्ट स्वरूप का उपयोग करके, वर्तमान ऑब्जेक्ट के मान को समतुल्य स्ट्रिंग प्रतिनिधित्व में बदलता है।

```cpp
String System::TimeSpan::ToString(const String &format) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const method

निर्दिष्ट स्वरूप और स्वरूप प्रदाता का उपयोग करके, वर्तमान ऑब्जेक्ट के मान को समतुल्य स्ट्रिंग प्रतिनिधित्व में बदलता है।

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const method




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const method




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```
## TimeSpan::ToString(const String\&, std::nullptr_t) const method




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
```
## देखें

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [TimeSpan](../)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)