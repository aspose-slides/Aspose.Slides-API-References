---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API संदर्भ
description: "डेलीगेट्स का संग्रह दर्शाता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या रेफ़रेंस द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए System::SmartPtr क्लास का कभी उपयोग न करें।"
type: docs
weight: 1093
url: /hi/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> क्लास

एक डेलीगेट्स का संग्रह दर्शाता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को वैल्यू या रेफ़रेंस द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी [System::SmartPtr](../smartptr/) क्लास का उपयोग न करें।

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | वर्णन |
| --- | --- |
| ReturnType | संग्रह में प्रत्येक डेलीगेट द्वारा इंगित इनवोक करने योग्य इकाइयों का रिटर्न टाइप |
| ArgumentTypes | संग्रह में प्रत्येक डेलीगेट द्वारा इंगित इनवोक करने योग्य इकाइयों की आर्गुमेंट सूची |

## विधियाँ

| मेथड | वर्णन |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | अभी कार्यान्वित नहीं किया गया है। |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | निर्दिष्ट डेलीगेट को संग्रह में जोड़ता है। |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | निर्दिष्ट फ़ंक्शन ऑब्जेक्ट को डेलीगेट संग्रह में जोड़ता है। फ़ंक्शन ऑब्जेक्ट को संग्रह में जोड़ने से पहले Callback डेलीगेट प्रकार में रूपांतरित किया जाता है। |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | निर्दिष्ट MulticastDelegate ऑब्जेक्ट को डेलीगेट संग्रह में जोड़ता है। |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | निर्दिष्ट ऑब्जेक्ट की निर्दिष्ट non-static मेथड को डेलीगेट संग्रह में जोड़ता है। |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | निर्दिष्ट ऑब्जेक्ट की निर्दिष्ट non-static मेथड को डेलीगेट संग्रह में जोड़ता है। |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | निर्दिष्ट डेलीगेट को डेलीगेट संग्रह से हटाता है। |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | निर्दिष्ट ऑब्जेक्ट की निर्दिष्ट non-static मेथड को डेलीगेट संग्रह से हटाता है। |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | निर्दिष्ट ऑब्जेक्ट की निर्दिष्ट non-static मेथड को डेलीगेट संग्रह से हटाता है। |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | निर्दिष्ट MulticastDelegate ऑब्जेक्ट को डेलीगेट संग्रह से हटाता है। |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | डेलीगेट संग्रह से सभी डेलीगेट हटाता है। |
| **bool** [empty](./empty/)() const | निर्धारित करता है कि डेलीगेट संग्रह खाली है या नहीं। |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | अभी कार्यान्वित नहीं किया गया है। |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | वर्तमान में डेलीगेट संग्रह में मौजूद सभी डेलीगेट को कॉल करता है। डेलीगेट उसी क्रम में बुलाए जाते हैं जैसा कि उन्हें संग्रह में जोड़ा गया था। मेथड तब तक ब्लॉक रहता है जब तक डेलीगेट निष्पादित होते हैं। |
| **bool** [IsNull](./isnull/)() const | निर्धारित करता है कि डेलीगेट संग्रह खाली है या नहीं। |
|  [MulticastDelegate](./multicastdelegate/)() | एक खाली संग्रह बनाता है। |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | डिफ़ॉल्ट कंस्ट्रक्टर के समान। |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | डेलीगेट संग्रह की सतही कॉपी करता है। |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | मूविंग कंस्ट्रक्टर। |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | एक इंस्टेंस बनाता है और निर्दिष्ट डेलीगेट को डेलीगेट संग्रह में जोड़ता है। |
|  [MulticastDelegate](./multicastdelegate/)(T) | एक इंस्टेंस बनाता है और निर्दिष्ट मान को डेलीगेट संग्रह में जोड़ता है। |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | एक इंस्टेंस बनाता है और निर्दिष्ट मान को डेलीगेट संग्रह में जोड़ता है। |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | निर्धारित करता है कि डेलीगेट संग्रह खाली नहीं है। |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | निर्धारित करता है कि दो MulticastDelegate इंस्टेंस - वर्तमान ऑब्जेक्ट और निर्दिष्ट ऑब्जेक्ट - असमान हैं या नहीं। |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | वर्तमान में डेलीगेट संग्रह में मौजूद सभी डेलीगेट को कॉल करता है। डेलीगेट उसी क्रम में बुलाए जाते हैं जैसा कि उन्हें संग्रह में जोड़ा गया था। ऑपरेटर तब तक ब्लॉक रहता है जब तक डेलीगेट निष्पादित होते हैं। |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | निर्दिष्ट डेलीगेट को संग्रह में जोड़ता है। |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | निर्दिष्ट डेलीगेट को डेलीगेट संग्रह से हटाता है। |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डेलीगेट संग्रह को वर्तमान ऑब्जेक्ट को असाइन करता है। परिणामस्वरूप दोनों ऑब्जेक्ट समान डेलीगेट संग्रह की ओर संकेत करते हैं। |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | मूविंग असाइनमेंट ऑपरेटर। |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | निर्धारित करता है कि डेलीगेट संग्रह खाली है या नहीं। |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | निर्धारित करता है कि दो MulticastDelegate इंस्टेंस - वर्तमान ऑब्जेक्ट और निर्दिष्ट ऑब्जेक्ट - समान हैं या नहीं। |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | खाली (वास्तव में कुछ नहीं कॉल करने वाले) कॉन्टेन्ड कॉलबैक को साफ़ करता है। |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | MulticastDelegate क्लास टाइप जानकारी दर्शाने वाले [TypeInfo](../typeinfo/) ऑब्जेक्ट का रेफ़रेंस लौटाता है। |
|  [~MulticastDelegate](./~multicastdelegate/)() | डिस्ट्रक्टर। |

## टाइपडिफ़

| टाइपडिफ़ | वर्णन |
| --- | --- |
| [Callback](./callback/) | MulticastDelegate क्लास द्वारा प्रतिनिधित्व किए गए डेलीगेट का प्रकार। |
| [Function](./function/) | डेलीगेट सिग्नेचर से संबंधित फ़ंक्शन का प्रकार। |

## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)