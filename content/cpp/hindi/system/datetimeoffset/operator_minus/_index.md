---
title: operator-()
second_title: Aspose.Slides के लिये C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से निर्दिष्ट टाइम स्पैन को घटाने के परिणामस्वरूप प्राप्त तिथि और समय मान को दर्शाते हुए DateTimeOffset क्लास की नई इंस्टेंस लौटाता है।
type: docs
weight: 521
url: /hi/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const मेथड

वापस एक नई [DateTimeOffset](../) क्लास की इंस्टेंस देता है जो उस तिथि और समय मान को दर्शाती है जो वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से निर्दिष्ट टाइम स्पैन को घटाने के परिणामस्वरूप प्राप्त होता है।

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | घटाने के लिये एक समय अंतराल |

### रिटर्न वैल्यू

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से **value** को घटाने के परिणामस्वरूप प्राप्त तिथि और समय मान को दर्शाने वाली [DateTimeOffset](../) क्लास की नई इंस्टेंस लौटाता है।

## DateTimeOffset::operator-(const DateTimeOffset\&) const मेथड

वापस [TimeSpan](../../timespan/) क्लास की एक इंस्टेंस देता है जो वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा प्रतिनिधित्व किए गए तिथि और समय मानों के बीच के समय अंतराल को दर्शाती है।

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | एक [DateTime](../../datetime/) क्लास की इंस्टेंस जो गणना किए जाने वाले अंतराल के एक सिरे को दर्शाती है |

### रिटर्न वैल्यू

वर्तमान ऑब्जेक्ट और **other** द्वारा प्रतिनिधित्व किए गए तिथि और समय मानों के बीच के समय अंतराल को दर्शाने वाली [TimeSpan](../../timespan/) क्लास की इंस्टेंस लौटाता है।

## संदर्भ

* क्लास [DateTimeOffset](../)
* क्लास [TimeSpan](../../timespan/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)