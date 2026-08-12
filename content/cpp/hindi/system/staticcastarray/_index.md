---
title: StaticCastArray()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट एरे के तत्वों को विभिन्न प्रकार में कास्ट करता है। उन मामलों के लिए ओवरराइड जहाँ From SmartPtr ऑब्जेक्ट है।
type: docs
weight: 2978
url: /hi/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function


निर्दिष्ट एरे के तत्वों को अलग प्रकार में कास्ट करता है। उन मामलों के लिए ओवरराइड जहाँ From [SmartPtr](../smartptr/) ऑब्जेक्ट है।

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| To | निर्दिष्ट एरे के तत्वों को कास्ट करने के लिए लक्ष्य प्रकार |
| From | उन तत्वों का प्रकार जिनके तत्वों को कास्ट किया जाना है |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | कास्ट करने वाले तत्वों वाले एरे के लिए साझा पोइंटर |

### रिटर्न मान

एक नया एरे जिसका पॉइंटर **To** प्रकार के तत्वों को रखता है, जो **from** के तत्वों के समतुल्य है

अवप्रचलित
:   पिछले संगतता के लिए जोड़ा गया। इसके बजाय ExplicitCast का उपयोग करें।

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function


निर्दिष्ट एरे के तत्वों को अलग प्रकार में कास्ट करता है। उन मामलों के लिए ओवरराइड जहाँ From Boxable है और To [Object](../object/)[] है।

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| To | निर्दिष्ट एरे के तत्वों को कास्ट करने के लिए लक्ष्य प्रकार |
| From | उन तत्वों का प्रकार जिनके तत्वों को कास्ट किया जाना है |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | कास्ट करने वाले तत्वों वाले एरे के लिए साझा पोइंटर |

### रिटर्न मान

एक नया एरे जिसका पॉइंटर **To** प्रकार के तत्वों को रखता है, जो **from** के तत्वों के समतुल्य है

अवप्रचलित
:   पिछले संगतता के लिए जोड़ा गया। इसके बजाय ExplicitCast का उपयोग करें।

## संबंधित देखें

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Class [Object](../object/)
* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsBoxable](../isboxable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)