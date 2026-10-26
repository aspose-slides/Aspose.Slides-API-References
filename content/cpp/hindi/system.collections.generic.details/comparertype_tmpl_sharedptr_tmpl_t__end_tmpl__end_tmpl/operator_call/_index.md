---
title: operator()()
second_title: Aspose.Slides for C++ API संदर्भ
description: IComparable इंटरफ़ेस को लागू करने वाले पॉइंटर प्रकारों की तुलना करता है।
type: docs
weight: 1
url: /hi/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const विधि


[IComparable](../../../system/icomparable/) इंटरफ़ेस को लागू करने वाले पॉइंटर प्रकारों की तुलना करता है।

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | तुलना करने के लिए प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | बाएँ हाथ का मान। |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | दाएँ हाथ का मान। |

### वापसी मान

**a** को **b** से छोटा माना जाता है तो सत्य, अन्यथा असत्य।

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const विधि


[IComparable](../../../system/icomparable/) इंटरफ़ेस को लागू नहीं करने वाले पॉइंटर प्रकारों की तुलना करता है।

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | तुलना करने के लिए प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | बाएँ हाथ का मान। |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | दाएँ हाथ का मान। |

### वापसी मान

**a** को **b** से छोटा माना जाता है तो सत्य, अन्यथा असत्य।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* नेमस्पेस [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)