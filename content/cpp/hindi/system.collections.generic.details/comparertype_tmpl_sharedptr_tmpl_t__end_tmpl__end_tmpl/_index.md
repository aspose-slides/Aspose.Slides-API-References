---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: तत्वों की तुलना 'less' सिद्धांत का उपयोग करके करता है।
type: docs
weight: 157
url: /hi/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

तत्वों की तुलना 'less' सिद्धांत का उपयोग करके करता है।

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तुलना किए गए तत्वों का प्रकार। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | [IComparable](../../system/icomparable/) इंटरफ़ेस को लागू करने वाले पॉइंटर प्रकारों की तुलना करता है। |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | [IComparable](../../system/icomparable/) इंटरफ़ेस को लागू नहीं करने वाले पॉइंटर प्रकारों की तुलना करता है। |

## देखें भी

* नेमस्पेस [System::Collections::Generic::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)