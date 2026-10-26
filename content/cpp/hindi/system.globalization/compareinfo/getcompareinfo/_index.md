---
title: GetCompareInfo()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित संस्कृति से संबंधित CompareInfo प्राप्त करता है और निर्धारित असेंबली में स्ट्रिंग तुलना विधियों का उपयोग करता है।
type: docs
weight: 183
url: /hi/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) विधि

[CompareInfo](../) प्राप्त करता है जो निर्दिष्ट संस्कृति से सम्बंधित है और निर्दिष्ट असेंबली में स्ट्रिंग तुलना विधियों का उपयोग करता है।

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| culture | int | संस्कृति पहचानकर्ता (LCID)। |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | स्ट्रिंग तुलना विधियों को समाहित करने वाली असेंबली। |

### रिटर्न वैल्यू

[CompareInfo](../) ऑब्जेक्ट।

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) विधि

[CompareInfo](../) प्राप्त करता है जो निर्दिष्ट संस्कृति से सम्बंधित है और निर्दिष्ट असेंबली में स्ट्रिंग तुलना विधियों का उपयोग करता है।

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | संस्कृति नाम। |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | स्ट्रिंग तुलना विधियों को समाहित करने वाली असेंबली। |

### रिटर्न वैल्यू

[CompareInfo](../) ऑब्जेक्ट।

## CompareInfo::GetCompareInfo(int) विधि

[CompareInfo](../) प्राप्त करता है जो निर्दिष्ट संस्कृति से सम्बंधित है।

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| culture | int | संस्कृति पहचानकर्ता (LCID)। |

### रिटर्न वैल्यू

[CompareInfo](../) ऑब्जेक्ट।

## CompareInfo::GetCompareInfo(const String\&) विधि

[CompareInfo](../) प्राप्त करता है जो निर्दिष्ट संस्कृति से सम्बंधित है।

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | संस्कृति नाम। |

### रिटर्न वैल्यू

[CompareInfo](../) ऑब्जेक्ट।

## और देखें

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Assembly](../../../system.reflection/assembly/)
* क्लास [CompareInfo](../)
* क्लास [String](../../../system/string/)
* नामस्थान [System::Globalization](../../)
* लाइब्रेरी [Aspose.Slides](../../../)