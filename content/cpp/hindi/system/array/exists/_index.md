---
title: Exists()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि निर्दिष्ट Array ऑब्जेक्ट में कोई ऐसा तत्व है जो निर्दिष्ट प्रेडिकेट की आवश्यकताओं को पूरा करता हो।
type: docs
weight: 781
url: /hi/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) मेथड

निर्धारित करता है कि निर्दिष्ट [Array](../) ऑब्जेक्ट में कोई तत्व है या नहीं जो निर्दिष्ट प्रेडिकेट की आवश्यकताओं को पूरा करता हो।

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### आर्ग्युमेंट्स

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | वह ऐरे जिसमें तत्व को खोजा जाना है |
| match | std::function\<**bool**(T)> | फ़ंक्शन ऑब्जेक्ट जो आवश्यकताओं को परिभाषित करता है और जाँचता है कि कोई तत्व उन्हें पूरा करता है या नहीं |

### वापसी मान

यदि **arr** में कोई ऐसा तत्व हो जो **match** द्वारा परिभाषित आवश्यकताओं को पूरा करता हो तो सत्य

## संबंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* क्लास [Array](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)