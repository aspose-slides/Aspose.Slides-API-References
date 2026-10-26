---
title: Subtract()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान से निर्दिष्ट समय अंतराल को घटाने के परिणामस्वरूप प्राप्त तिथि और समय मान को दर्शाने वाली DateTime class का एक नया उदाहरण लौटाता है।
type: docs
weight: 326
url: /hi/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const विधि

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान से निर्दिष्ट समय अंतराल को घटाने के परिणामस्वरूप प्राप्त तिथि-समय मान को दर्शाने वाली [DateTime](../) क्लास की एक नई उदाहरण लौटाता है।

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | घटाने के लिये एक समय अंतराल |

### वापसी मान

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान से **duration** को घटाने के परिणामस्वरूप प्राप्त तिथि-समय मान को दर्शाने वाली [DateTime](../) क्लास की एक नई उदाहरण।

## DateTime::Subtract(DateTime) const विधि

वर्तमान और निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए तिथि-समय मानों के बीच के समय अंतराल को दर्शाने वाली [TimeSpan](../../timespan/) क्लास का एक उदाहरण लौटाता है।

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [DateTime](../) | [DateTime](../) क्लास का एक उदाहरण जो गणना किए जाने वाले अंतराल के एक अंत को निरूपित करता है |

### वापसी मान

वर्तमान ऑब्जेक्ट और **value** द्वारा दर्शाए गए तिथि-समय मानों के बीच के समय अंतराल को दर्शाने वाली [TimeSpan](../../timespan/) क्लास का एक उदाहरण।

## देखें

* क्लास [DateTime](../)
* क्लास [TimeSpan](../../timespan/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)