---
title: Delegate()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिफ़ॉल्ट कन्स्ट्रक्टर। डेलीगेट ऑब्जेक्ट बनाता है जो किसी भी चीज़ की ओर संकेत नहीं करता।
type: docs
weight: 1
url: /hi/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() विधि

डिफ़ॉल्ट कन्स्ट्रक्टर। एक डेलीगेट ऑब्जेक्ट बनाता है जो किसी भी चीज़ की ओर संकेत नहीं करता।

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) विधि




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) विधि

मूविंग कॉपी कन्स्ट्रक्टर। निर्दिष्ट डेलीगेट द्वारा संकेतित इकाई का स्वामित्व लेता है।

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| o | Delegate\&& | डेलीगेट ऑब्जेक्ट जो संकेतित इकाई को स्थानांतरित करने के लिए उपयोग किया जाता है। |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) विधि

कन्स्ट्रक्टर। निर्दिष्ट फ्री फ़ंक्शन या स्टैटिक मेथड के पॉइंटर से एक डेलीगेट ऑब्जेक्ट बनाता है।

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| यह | कन्स्ट्रक्टर द्वारा एक तर्क के रूप में स्वीकार किए गए फ़ंक्शन या स्टैटिक मेथड पॉइंटर का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| function | T | फ़ंक्शन या स्टैटिक मेथड का पॉइंटर जिसे नए निर्मित डेलीगेट इंस्टेंस द्वारा संकेतित किया जाएगा। |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) विधि

कन्स्ट्रक्टर। std::bind() द्वारा उत्पन्न फ़ंक्शन ऑब्जेक्ट के पॉइंटर से एक डेलीगेट बनाता है।

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| यह | std::bind() द्वारा उत्पन्न फ़ंक्शन ऑब्जेक्ट का प्रकार जो कन्स्ट्रक्टर द्वारा एक तर्क के रूप में स्वीकार किया जाता है |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| function | T | \"bind expression\" – std::bind() द्वारा उत्पन्न फ़ंक्शन पॉइंटर – जिसे नए निर्मित डेलीगेट इंस्टेंस द्वारा संकेतित किया जाएगा। |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) विधि

कन्स्ट्रक्टर। निर्दिष्ट फ़ंक्शन ऑब्जेक्ट से एक डेलीगेट बनाता है।

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | कन्स्ट्रक्टर द्वारा एक तर्क के रूप में स्वीकार किए गए फ़ंक्शन ऑब्जेक्ट का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functor_tag | int | एक डमी पूर्णांक मान; यह तर्क अस्पष्टता को हल करने के लिए उपयोग किया जाता है |
| functor | T\& | वह फ़ंक्शन ऑब्जेक्ट जिसपर नया निर्मित डेलीगेट संकेत करेगा |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) विधि

मूविंग कन्स्ट्रक्टर। निर्दिष्ट फ़ंक्शन ऑब्जेक्ट से एक डेलीगेट बनाता है।

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | कन्स्ट्रक्टर द्वारा एक तर्क के रूप में स्वीकार किए गए फ़ंक्शन ऑब्जेक्ट का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functor_tag | long | एक डमी पूर्णांक मान; यह तर्क अस्पष्टता को हल करने के लिए उपयोग किया जाता है |
| functor | T\&& | वह फ़ंक्शन ऑब्जेक्ट जिसपर नया निर्मित डेलीगेट संकेत करेगा |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) विधि

कन्स्ट्रक्टर। निर्दिष्ट ऑब्जेक्ट के निर्दिष्ट नॉन-स्टैटिक मेथड की ओर संकेत करने वाला डेलीगेट बनाता है।

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| MemberType | कन्स्ट्रक्टर द्वारा एक तर्क के रूप में स्वीकार किए गए नॉन-स्टैटिक मेथड का प्रकार |
| ClassType | कन्स्ट्रक्टर द्वारा एक तर्क के रूप में स्वीकार किए गए ऑब्जेक्ट का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| member | MemberType ClassType::* | नॉन-स्टैटिक मेथड का पॉइंटर जिससे नया निर्मित डेलीगेट संकेत करेगा |
| obj | ClassType * | उस ऑब्जेक्ट की ओर संकेत करने वाला पॉइंटर जिसका मेथड नया निर्मित डेलीगेट संकेत करेगा |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) विधि

कन्स्ट्रक्टर। निर्दिष्ट ऑब्जेक्ट के निर्दिष्ट नॉन-स्टैटिक मेथड की ओर संकेत करने वाला डेलीगेट बनाता है।

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| MemberType | कन्स्ट्रक्टर द्वारा एक तर्क के रूप में स्वीकार किए गए नॉन-स्टैटिक मेथड का प्रकार |
| ClassType | कन्स्ट्रक्टर द्वारा एक तर्क के रूप में स्वीकार किए गए ऑब्जेक्ट का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| member | MemberType MemberClass::* | नॉन-स्टैटिक मेथड का पॉइंटर जिससे नया निर्मित डेलीगेट संकेत करेगा |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | एक शैर्ड पॉइंटर जो उस ऑब्जेक्ट के मेथड की ओर संकेत करेगा जिससे नया निर्मित डेलीगेट संकेत करेगा |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) विधि

एक std::function फ़ंक्शन ऑब्जेक्ट की ओर संकेत करने वाला डेलीगेट ऑब्जेक्ट बनाता है।

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| R | कन्स्ट्रक्टर द्वारा एक तर्क के रूप में स्वीकार किए गए फ़ंक्शन ऑब्जेक्ट का रिटर्न टाइप |
| Args | कन्स्ट्रक्टर द्वारा एक तर्क के रूप में स्वीकार किए गए फ़ंक्शन ऑब्जेक्ट की आर्ग्यूमेंट सूची |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| f | std::function\<R(Args...)> | वह फ़ंक्शन ऑब्जेक्ट जिसे नया निर्मित डेलीगेट ऑब्जेक्ट संकेत करेगा |

## संदर्भ

* टाइपडिफ [SharedPtr](../../sharedptr/)
* क्लास [Delegate< ReturnType(ArgumentTypes...)>](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)