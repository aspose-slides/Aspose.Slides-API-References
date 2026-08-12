---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides for C++ API संदर्भ
description: सीक्वेंस का पहला तत्व लौटाता है, या यदि सीक्वेंस खाली है तो डिफ़ॉल्ट मान देता है।
type: docs
weight: 66
url: /hi/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() मेथड

सीक्वेंस का पहला तत्व लौटाता है, या यदि सीक्वेंस खाली है तो डिफ़ॉल्ट मान देता है।

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### रिटर्न मान

सीक्वेंस में पहला तत्व या यदि सीक्वेंस खाली है तो डिफ़ॉल्ट-निर्मित मान।

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) मेथड

सीक्वेंस का वह पहला तत्व लौटाता है जो शर्त को पूरा करता है, या यदि ऐसा कोई तत्व नहीं मिलता तो डिफ़ॉल्ट मान।

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | प्रत्येक तत्व को शर्त के लिए परीक्षण करने वाला फ़ंक्शन। |

### रिटर्न मान

यदि स्रोत खाली है या predicate द्वारा निर्दिष्ट परीक्षण पास करने वाला कोई तत्व नहीं मिलता तो default(T); अन्यथा, स्रोत में वह पहला तत्व जो predicate द्वारा निर्दिष्ट परीक्षण पास करता है।

## और देखें

* क्लास [IEnumerable](../)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)