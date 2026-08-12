---
title: ParseExact()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट फ़ॉर्मेट और संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके एक तिथि और समय मान की निर्दिष्ट स्ट्रिंग प्रतिनिधित्व को समकक्ष DateTime ऑब्जेक्ट में परिवर्तित करता है। स्ट्रिंग प्रतिनिधित्व का फ़ॉर्मेट बिल्कुल निर्दिष्ट फ़ॉर्मेट से मेल खाना चाहिए। यदि रूपांतरण विफल होता है तो एक अपवाद फेंका जाता है।
type: docs
weight: 872
url: /hi/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) विधि


निर्दिष्ट स्ट्रिंग प्रतिनिधित्व को निर्दिष्ट फ़ॉर्मेट और संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके समकक्ष [DateTime](../) ऑब्जेक्ट में परिवर्तित करता है। स्ट्रिंग प्रतिनिधित्व का फ़ॉर्मेट बिल्कुल निर्दिष्ट फ़ॉर्मेट से मेल खाना चाहिए। यदि रूपांतरण विफल हो जाता है तो एक अपवाद फेंका जाता है।

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | परिवर्तित करने के लिए तिथि और समय मान की स्ट्रिंग प्रतिनिधित्व। |
| format | const [String](../../string/)\& | स्ट्रिंग फ़ॉर्मेट। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी प्रदान करने वाला [IFormatProvider](../../iformatprovider/) ऑब्जेक्ट। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | एक बिटवाइज़ संयोजन जो एन्यूमेरेशन मानों का होता है और यह **s** के बारे में अतिरिक्त जानकारी, **s** में मौजूद शैली तत्वों या **s** से [DateTime](../) ऑब्जेक्ट में रूपांतरण के बारे में जानकारी देता है। |

### वापसी मान

एक नया [DateTime](../) क्लास का इंस्टेंस जो निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए तिथि और समय मान के समकक्ष है।

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) विधि




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) विधि 




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) विधि 




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) विधि


निर्दिष्ट स्ट्रिंग प्रतिनिधित्व को निर्दिष्ट फ़ॉर्मेट्स, संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी और शैली का उपयोग करके समकक्ष [DateTime](../) ऑब्जेक्ट में परिवर्तित करता है। स्ट्रिंग प्रतिनिधित्व का फ़ॉर्मेट निर्दिष्ट फ़ॉर्मेट्स में से एक या अधिक से बिल्कुल मेल खाना चाहिए। यदि रूपांतरण विफल हो जाता है तो एक अपवाद फेंका जाता है।

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | परिवर्तित करने के लिए तिथि और समय मान की स्ट्रिंग प्रतिनिधित्व। |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | स्ट्रिंग फ़ॉर्मेट्स की ऐरे। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी प्रदान करने वाला [IFormatProvider](../../iformatprovider/) ऑब्जेक्ट। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | एक बिटवाइज़ संयोजन जो एन्यूमेरेशन मानों का होता है और यह **s** के बारे में अतिरिक्त जानकारी, **s** में मौजूद शैली तत्वों या **s** से [DateTime](../) ऑब्जेक्ट में रूपांतरण के बारे में जानकारी देता है। |

### वापसी मान

एक नया [DateTime](../) क्लास का इंस्टेंस जो निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए तिथि और समय मान के समकक्ष है।

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) विधि 




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) विधि 




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) विधि 




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## संबंधित देखें

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)