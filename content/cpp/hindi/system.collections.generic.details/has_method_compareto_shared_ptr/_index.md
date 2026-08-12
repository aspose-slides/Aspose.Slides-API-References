---
title: has_method_compareto_shared_ptr
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "जाँचता है कि निर्दिष्ट प्रकार में CompareTo(SharedPtr<T>) मेथड मौजूद है या नहीं। यदि हाँ, तो std::true_type को विरासत में लेता है, अन्यथा std::false_type को विरासत में लेता है। इसे std::enable_if में इस्तेमाल किया जा सकता है।"
type: docs
weight: 183
url: /hi/system.collections.generic.details/has_method_compareto_shared_ptr/
---
## has_method_compareto_shared_ptr संरचना

जाँचता है कि CompareTo(SharedPtr<T>) मेथड निर्दिष्ट प्रकार में मौजूद है। यदि ऐसा है, तो std::true_type को विरासति करता है, अन्यथा std::false_type को विरासति करता है। इसे std::enable_if में उपयोग किया जा सकता है।

```cpp
template<typename T,typename Sfinae>class has_method_compareto_shared_ptr : public std::false_type
```

### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T | Equals मेथड के अस्तित्व की जाँच के लिये प्रकार। |
| Sfinae | SFINAE के काम करने के लिये औपचारिक टेम्प्लेट आर्ग्युमेंट। |

## संबंधित देखें

* नामस्थान [System::Collections::Generic::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)