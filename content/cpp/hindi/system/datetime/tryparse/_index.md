---
title: TryParse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट तिथि और समय मान के स्ट्रिंग प्रतिनिधित्व को समकक्ष DateTime ऑब्जेक्ट में परिवर्तित करता है।
type: docs
weight: 885
url: /hi/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) विधि

निर्दिष्ट तिथि और समय मान के स्ट्रिंग प्रतिनिधित्व को समकक्ष [DateTime](../) ऑब्जेक्ट में परिवर्तित करता है।

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | रूपांतरण के लिए तिथि और समय मान के स्ट्रिंग प्रतिनिधित्व। |
| result | [DateTime](../)\& | आउटपुट आर्ग्युमेंट जो, यदि रूपांतरण सफल हो तो, रूपांतरण परिणाम रखता है। |

### वापसी मान

True यदि रूपांतरण सफल हो तो, अन्यथा - false।

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) विधि

निर्दिष्ट तिथि और समय मान के स्ट्रिंग प्रतिनिधित्व को निर्दिष्ट संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी और शैली का उपयोग करके समकक्ष [DateTime](../) ऑब्जेक्ट में परिवर्तित करता है।

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | रूपांतरण के लिए तिथि और समय मान के स्ट्रिंग प्रतिनिधित्व। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी प्रदान करने वाला [IFormatProvider](../../iformatprovider/) ऑब्जेक्ट। |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | उन **s** के बारे में अतिरिक्त जानकारी प्रदान करने वाले enumeration मानों का बिटवाइज़ संयोजन, शैली तत्व जो **s** में मौजूद हो सकते हैं, या **s** से एक [DateTime](../) ऑब्जेक्ट में रूपांतरण के बारे में। |
| result | [DateTime](../)\& | आउटपुट आर्ग्युमेंट जो, यदि रूपांतरण सफल हो तो, रूपांतरण परिणाम रखता है। |

### वापसी मान

True यदि रूपांतरण सफल हो तो, अन्यथा - false।

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) विधि

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) विधि

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) विधि

```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## संबंधित देखें

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)