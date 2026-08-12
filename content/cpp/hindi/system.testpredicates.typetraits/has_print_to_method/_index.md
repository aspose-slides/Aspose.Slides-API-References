---
title: has_print_to_method
second_title: Aspose.Slides for C++ API संदर्भ
description: "PrintTo फ़ंक्शन के ओवरलोड की जांच करता है जो दिए गए प्रकार को पहले तर्क के रूप में लेता है। यदि एक ओवरलोड मौजूद है, तो std::true_type को विरासत में प्राप्त करता है, अन्यथा std::false_type को विरासत में प्राप्त करता है।"
type: docs
weight: 27
url: /hi/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

PrintTo फ़ंक्शन के ओवरलोड की जांच करता है जो दिए गए प्रकार को पहले तर्क के रूप में लेता है। यदि एक ओवरलोड मौजूद है, तो std::true_type को विरासत में प्राप्त करता है, अन्यथा std::false_type को विरासत में प्राप्त करता है।

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | जाँच करने के लिए प्रकार। |
| Enable | SFINAE के कार्य करने के लिए औपचारिक तर्क। |

## देखें

* नेमस्पेस [System::TestPredicates::TypeTraits](../)
* लाइब्रेरी [Aspose.Slides](../../)