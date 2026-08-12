---
title: StartsWith()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: जाँचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग से शुरू होती है।
type: docs
weight: 469
url: /hi/system/string/startswith/
---
## String::StartsWith(const String\&) const method


जाँचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग से शुरू होती है।

```cpp
bool System::String::StartsWith(const String &value) const
```


### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../)\& | लुकअप स्ट्रिंग। |

### Return Value

true if string starts with specified substring, false otherwise.

## String::StartsWith(const String\&, System::StringComparison) const method


जाँचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग से शुरू होती है।

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```


### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../)\& | लुकअप स्ट्रिंग। |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड, अधिक जानकारी के लिए [System::StringComparison](../../stringcomparison/) देखें। |

### Return Value

true if string starts with specified substring, false otherwise.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method


जाँचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग से शुरू होती है।

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../)\& | लुकअप स्ट्रिंग। |
| ignoreCase | **bool** | निर्दिष्ट करता है कि तुलना केस-इंसेंसिटिव है या नहीं। |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | स्ट्रिंग तुलना करते समय उपयोग करने के लिए संस्कृति। |

### Return Value

true if string starts with specified substring, false otherwise.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)