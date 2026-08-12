---
title: EndsWith()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जाँचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग के साथ समाप्त होती है।
type: docs
weight: 482
url: /hi/system/string/endswith/
---
## String::EndsWith(const String\&) const विधि


जाँचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग के साथ समाप्त होती है।

```cpp
bool System::String::EndsWith(const String &value) const
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../)\& | लुकअप स्ट्रिंग। |

### रिटर्न मान

true if string ends with specified substring, false otherwise.

## String::EndsWith(const String\&, System::StringComparison) const विधि


जाँचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग के साथ समाप्त होती है।

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../)\& | लुकअप स्ट्रिंग। |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड, विवरण के लिए [System::StringComparison](../../stringcomparison/) देखें। |

### रिटर्न मान

true if string ends with specified substring, false otherwise.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const विधि


जाँचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग के साथ समाप्त होती है।

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../)\& | लुकअप स्ट्रिंग। |
| ignoreCase | **bool** | निर्देश देता है कि तुलना केस-इन्सेंसिटिव है या नहीं। |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | स्ट्रिंग तुलना करते समय उपयोग की जाने वाली संस्कृति। |

### रिटर्न मान

true if string ends with specified substring, false otherwise.

## संबंधित देखें

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* वर्ग [String](../)
* वर्ग [CultureInfo](../../../system.globalization/cultureinfo/)
* नामस्थान [System](../../)
* Library [Aspose.Slides](../../../)