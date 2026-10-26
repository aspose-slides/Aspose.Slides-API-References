---
title: IsCppContainer
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "जाँचता है कि विशिष्ट प्रकार STL-स्टाइल कंटेनर है या नहीं। ऐसा करने के लिए, iterator और const_iterator सदस्य प्रकारों की उपस्थिति की जाँच करता है। यदि दोनों मौजूद हैं, तो std::true_type को विरासत में लेता है, अन्यथा std::false_type को विरासत में लेता है।"
type: docs
weight: 40
url: /hi/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

जाँचता है कि विशिष्ट प्रकार STL-स्टाइल कंटेनर है या नहीं। ऐसा करने के लिए, iterator और const_iterator सदस्य प्रकारों की उपस्थिति की जाँच करता है। यदि दोनों मौजूद हैं, तो std::true_type को विरासत में लेता है, अन्यथा std::false_type को विरासत में लेता है।

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### टेम्पलेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | जांचने के लिए प्रकार। |
| Enable | SFINAE के कार्य करने के लिए औपचारिक तर्क। |

## देखें भी

* नेमस्पेस [System::TestPredicates::TypeTraits](../)
* लाइब्रेरी [Aspose.Slides](../../)