---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: यह सहायक फ़ंक्शन यह निर्धारित करता है कि क्या विशेष क्लास में operator == मौजूद है।
type: docs
weight: 235
url: /hi/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) फ़ंक्शन

विशिष्ट क्लास में operator == है या नहीं, यह निर्धारित करने के लिये सहायक फ़ंक्शन।

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### टेम्पलेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T | जाँचने के लिये प्रकार। |
| Dummy | SFINAE जादू के लिये डमी तर्क। |

### रिटर्न मान

यदि operator == मौजूद है तो std::true_type का मान और अन्यथा false।

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) फ़ंक्शन

विशिष्ट क्लास में operator == है या नहीं, यह निर्धारित करने के लिये सहायक फ़ंक्शन।

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### रिटर्न मान

यदि operator == मौजूद है तो std::true_type का मान और अन्यथा false।

## देखें

* नामस्थान [System::Collections::Generic::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)