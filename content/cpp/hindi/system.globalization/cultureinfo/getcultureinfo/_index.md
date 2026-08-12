---
title: GetCultureInfo()
second_title: Aspose.Slides for C++ API संदर्भ
description: नाम से संस्कृति प्राप्त करता है। CreateSpecificCulture के समान।
type: docs
weight: 586
url: /hi/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) विधि

नाम से संस्कृति प्राप्त करता है। CreateSpecificCulture के समान।

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | पूर्वपरिभाषित संस्कृति नाम या मौज़ूद संस्कृति ऑब्जेक्ट का नाम। |

### वापसी मान

नया निर्मित संस्कृति ऑब्जेक्ट।

## CultureInfo::GetCultureInfo(const String\&, const String\&) विधि

नाम से संस्कृति प्राप्त करता है।

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | संस्कृति नाम। |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | [TextInfo](../../textinfo/) और [CompareInfo](../../compareinfo/) ऑब्जेक्ट्स के लिए उपयोग किया जाने वाला संस्कृति नाम। |

### वापसी मान

संस्कृति ऑब्जेक्ट।

## CultureInfo::GetCultureInfo(int32_t) विधि

आईडी द्वारा संस्कृति प्राप्त करता है।

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| culture | **int32_t** | संस्कृति पहचानकर्ता। |

### वापसी मान

नया निर्मित संस्कृति ऑब्जेक्ट।

## संबंधित देखें

* टाइपडेफ [CultureInfoPtr](../../cultureinfoptr/)
* क्लास [String](../../../system/string/)
* क्लास [CultureInfo](../)
* नेमस्पेस [System::Globalization](../../)
* लाइब्रेरी [Aspose.Slides](../../../)