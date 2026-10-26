---
title: CastEnumerableTo()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट एनेमेरेबल ऑब्जेक्ट के तत्वों को विभिन्न प्रकार में स्पष्ट रूप से कास्ट करता है।
type: docs
weight: 2965
url: /hi/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) फ़ंक्शन

निर्दिष्ट एनेमेरेबल ऑब्जेक्ट के तत्वों को विभिन्न प्रकार में स्पष्ट रूप से कास्ट करता है।

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| To | एनेमेरेबल ऑब्जेक्ट के तत्वों को स्थैतिक रूप से कास्ट करने के लिये प्रकार |
| From | एनेमेरेबल ऑब्जेक्ट का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| enumerable | const From\& | कास्ट करने के लिये तत्वों को सम्मिलित करने वाला एनेमेरेबल ऑब्जेक्ट |

### वापसी मान

एक नया संग्रह का पॉइंटर जो **To** प्रकार के तत्वों को समाहित करता है जो **enumerable** के तत्वों के समान होते हैं।

## System::CastEnumerableTo(const From\&) फ़ंक्शन

निर्दिष्ट एनेमेरेबल ऑब्जेक्ट के तत्वों को विभिन्न प्रकार में स्पष्ट रूप से कास्ट करता है।

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| To | एनेमेरेबल ऑब्जेक्ट के तत्वों को स्थैतिक रूप से कास्ट करने के लिये प्रकार |
| From | एनेमेरेबल ऑब्जेक्ट का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| enumerable | const From\& | एक Enumerable ऑब्जेक्ट का इनहेरिटर है जिसमें निर्धारित get_Count मेथड है और जिसमें कास्ट करने के लिये तत्व सम्मिलित हैं |

### वापसी मान

एक नया संग्रह का पॉइंटर जो **To** प्रकार के तत्वों को समाहित करता है जो **enumerable** के तत्वों के समान होते हैं।

## देखें

* क्लास [ListPtr](../../system.collections.generic/listptr/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)