---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API संदर्भ
description: "फ़ंक्शन, मेथड या फ़ंक्शन ऑब्जेक्ट का पॉइंटर दर्शाता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या रेफ़रेंस द्वारा पास किया जाना चाहिए। इस प्रकार के ऑब्जेक्ट को प्रबंधित करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 287
url: /hi/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> क्लास

फ़ंक्शन, मेथड या फ़ंक्शन ऑब्जेक्ट का पॉइंटर दर्शाता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और मान या रेफ़रेंस द्वारा फ़ंक्शनों को पास किया जाना चाहिए। इस प्रकार के ऑब्जेक्ट को प्रबंधित करने के लिए कभी भी [System::SmartPtr](../smartptr/) क्लास का उपयोग न करें।

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ReturnType | वह रिटर्न टाइप जो फ़ंक्शन, मेथड या फ़ंक्शन ऑब्जेक्ट पॉइंटर के लिए प्रतिनिधित्व करता है |
| ArgumentTypes | वह आर्ग्यूमेंट सूची जो फ़ंक्शन, मेथड या फ़ंक्शन ऑब्जेक्ट पॉइंटर के लिए प्रतिनिधित्व करता है |

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  [Delegate](./delegate/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। डेलीगेट ऑब्जेक्ट बनाता है जो किसी चीज़ की ओर संकेत नहीं करता है। |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | मूविंग कॉपी कन्स्ट्रक्टर। निर्दिष्ट डेलीगेट द्वारा संकेतित इकाई का स्वामित्व लेता है। |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | कन्स्ट्रक्टर। निर्दिष्ट फ़्री फ़ंक्शन या स्टैटिक मेथड पॉइंटर से डेलीगेट ऑब्जेक्ट बनाता है। |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | कन्स्ट्रक्टर। std::bind() द्वारा उत्पन्न फ़ंक्शन ऑब्जेक्ट पॉइंटर से डेलीगेट बनाता है। |
|  [Delegate](./delegate/)(int, T\&) | कन्स्ट्रक्टर। निर्दिष्ट फ़ंक्शन ऑब्जेक्ट से डेलीगेट बनाता है। |
|  [Delegate](./delegate/)(long, T\&&) | मूविंग कन्स्ट्रक्टर। निर्दिष्ट फ़ंक्शन ऑब्जेक्ट से डेलीगेट बनाता है। |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | कन्स्ट्रक्टर। निर्दिष्ट ऑब्जेक्ट के निर्दिष्ट नॉन-स्टैटिक मेथड की ओर संकेत करने वाला डेलीगेट बनाता है। |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | कन्स्ट्रक्टर। निर्दिष्ट ऑब्जेक्ट के निर्दिष्ट नॉन-स्टैटिक मेथड की ओर संकेत करने वाला डेलीगेट बनाता है। |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | std::function फ़ंक्शन ऑब्जेक्ट की ओर संकेत करने वाला डेलीगेट ऑब्जेक्ट बनाता है। |
| **bool** [Empty](./empty/)() const | निर्धारित करता है कि वर्तमान डेलीगेट ऑब्जेक्ट खाली है या नहीं, उदाहरण के लिए कोई इकाई संकेत नहीं करता। |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | वर्तमान डेलीगेट ऑब्जेक्ट द्वारा संकेतित फ़ंक्शन, मेथड या फ़ंक्शन ऑब्जेक्ट को कॉल करता है। |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | मूविंग असाइनमेंट ऑपरेटर। निर्दिष्ट डेलीगेट द्वारा संकेतित इकाई का स्वामित्व लेता है। |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | दो डेलीगेट ऑब्जेक्ट्स की तुलना करता है यह जांचने के लिए कि वे एक ही इकाई की ओर संकेत करते हैं या नहीं। |

## टिप्पणी

```cpp
#include "system/delegate.h"
#include <iostream"

// डेलीगेट को घोषित करें।
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // चर को PrintMessage फ़ंक्शन का पता असाइन करें।
  Message mes = Message(&PrintMessage);

  // फ़ंक्शन को कॉल करें।
  mes();

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
नमस्ते, दुनिया!
*/
```

## देखें भी

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)