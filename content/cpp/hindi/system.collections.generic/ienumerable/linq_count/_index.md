---
title: LINQ_Count()
second_title: Aspose.Slides for C++ API संदर्भ
description: सीक्वेंस में तत्वों की संख्या लौटाता है (सीधे गिनती द्वारा गणना किया गया)।
type: docs
weight: 118
url: /hi/system.collections.generic/ienumerable/linq_count/
---
## IEnumerable::LINQ_Count() विधि


सीक्वेंस में तत्वों की संख्या (सीधे गिनती द्वारा गणना) लौटाता है।

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count()
```


### रिटर्न मान

सीक्वेंस में तत्वों की संख्या।

## IEnumerable::LINQ_Count(const Func\<T, bool\>\&) विधि


सीक्वेंस में उन तत्वों की संख्या लौटाता है जो निर्दिष्ट शर्त को पूरा करते हैं।

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count(const Func<T, bool> &predicate)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| predicate | const [Func](../../../system/func/)\<T, **bool**\>\& | प्रत्येक तत्व को शर्त के लिये परीक्षण करने वाला फ़ंक्शन। |

### रिटर्न मान

निर्दिष्ट शर्त को पूरा करने वाले सीक्वेंस में तत्वों की संख्या।

## देखें

* क्लास [IEnumerable](../)
* क्लास [Func](../../../system/func/)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)