---
title: TryParseExact()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट तिथि और समय मान के स्ट्रिंग प्रतिनिधित्व को निर्दिष्ट फॉर्मेट, सांस्कृतिक-विशिष्ट फॉर्मेट जानकारी और शैली का उपयोग करके समतुल्य DateTime ऑब्जेक्ट में बदलता है। स्ट्रिंग प्रतिनिधित्व का फॉर्मेट निर्दिष्ट फॉर्मेट के बिल्कुल मेल खाना चाहिए।
type: docs
weight: 898
url: /hi/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method

निर्दिष्ट तिथि और समय मान के स्ट्रिंग प्रतिनिधित्व को निर्दिष्ट प्रारूप, सांस्कृतिक-विशिष्ट प्रारूप जानकारी और शैली का उपयोग करके समतुल्य [DateTime](../) ऑब्जेक्ट में परिवर्तित करता है। स्ट्रिंग प्रतिनिधित्व का प्रारूप निर्दिष्ट प्रारूप के बिल्कुल मेल खाना चाहिए।

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | कनवर्ट करने के लिए तिथि और समय मान के स्ट्रिंग प्रतिनिधित्व। |
| format | const [String](../../string/)\& | स्ट्रिंग प्रारूप। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | वह [IFormatProvider](../../iformatprovider/) ऑब्जेक्ट जो सांस्कृतिक-विशिष्ट प्रारूप जानकारी प्रदान करता है। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | बिटवाइज़ संयोजन जो **s** के बारे में अतिरिक्त जानकारी, **s** में मौजूद शैली तत्वों के बारे में, या **s** से [DateTime](../) ऑब्जेक्ट में परिवर्तन के बारे में प्रदान करता है। |
| result | [DateTime](../)\& | आउटपुट आर्ग्यूमेंट जो, यदि रूपांतरण सफल होता है, तो रूपांतरण का परिणाम रखता है। |

### Return Value

यदि रूपांतरण सफल होता है तो true, अन्यथा - false।

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method

निर्दिष्ट तिथि और समय मान के स्ट्रिंग प्रतिनिधित्व को निर्दिष्ट फॉर्मैट्स, सांस्कृतिक-विशिष्ट प्रारूप जानकारी और शैली का उपयोग करके समतुल्य [DateTime](../) ऑब्जेक्ट में परिवर्तित करता है। स्ट्रिंग प्रतिनिधित्व का प्रारूप निर्दिष्ट फॉर्मैट्स में से एक या अधिक के बिल्कुल मेल खाना चाहिए।

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | कनवर्ट करने के लिए तिथि और समय मान के स्ट्रिंग प्रतिनिधित्व। |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | स्ट्रिंग फॉर्मैट्स की एरे। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | वह [IFormatProvider](../../iformatprovider/) ऑब्जेक्ट जो सांस्कृतिक-विशिष्ट प्रारूप जानकारी प्रदान करता है। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | बिटवाइज़ संयोजन जो **s** के बारे में अतिरिक्त जानकारी, **s** में मौजूद शैली तत्वों के बारे में, या **s** से [DateTime](../) ऑब्जेक्ट में परिवर्तन के बारे में प्रदान करता है। |
| result | [DateTime](../)\& | आउटपुट आर्ग्यूमेंट जो, यदि रूपांतरण सफल होता है, तो रूपांतरण का परिणाम रखता है। |

### Return Value

यदि रूपांतरण सफल होता है तो true, अन्यथा - false।

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)