---
title: connect()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट डेलीगेट को संग्रह में जोड़ता है।
type: docs
weight: 144
url: /hi/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) विधि

निर्दिष्ट डेलीगेट को संग्रह में जोड़ता है।

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [Callback](../callback/) | संग्रह में जोड़ने के लिए डेलीगेट |

### वापसी मान

स्वयं का संदर्भ

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) विधि

निर्दिष्ट फ़ंक्शन ऑब्जेक्ट को डेलीगेट संग्रह में जोड़ता है। फ़ंक्शन ऑब्जेक्ट को संग्रह में जोड़ने से पहले Callback डेलीगेट प्रकार में परिवर्तित किया जाता है।

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| R | संग्रह में जोड़ने के लिए फ़ंक्शन ऑब्जेक्ट का रिटर्न प्रकार |
| Args | संग्रह में जोड़ने के लिए फ़ंक्शन ऑब्जेक्ट की आर्ग्युमेंट सूची |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| f | std::function\<R(Args...)> | संग्रह में जोड़ने के लिए फ़ंक्शन ऑब्जेक्ट |

### वापसी मान

स्वयं का संदर्भ

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) विधि

निर्दिष्ट MulticastDelegate ऑब्जेक्ट को डेलीगेट संग्रह में जोड़ता है।

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | संग्रह में जोड़ने के लिए MulticastDelegate क्लास का एक इंस्टेंस |

### वापसी मान

स्वयं का संदर्भ

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) विधि

निर्दिष्ट वस्तु की निर्दिष्ट नॉन-स्टैटिक मेथड को डेलीगेट संग्रह में जोड़ता है।

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| MemberType | संग्रह में जोड़ने के लिए नॉन-स्टैटिक मेथड का प्रकार |
| ClassType | वह वस्तु का प्रकार जिसके मेथड को संग्रह में जोड़ना है |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| member | MemberType ClassType::* | निर्दिष्ट वस्तु की नॉन-स्टैटिक मेथड का पॉइंटर |
| obj | ClassType * | वह वस्तु जिसका मेथड संग्रह में जोड़ना है, उसका पॉइंटर |

### वापसी मान

स्वयं का संदर्भ

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) विधि

निर्दिष्ट वस्तु की निर्दिष्ट नॉन-स्टैटिक मेथड को डेलीगेट संग्रह में जोड़ता है।

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| MemberType | संग्रह में जोड़ने के लिए नॉन-स्टैटिक मेथड का प्रकार |
| ClassType | वह वस्तु जिसका मेथड संग्रह में जोड़ना है, उसका प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| member | MemberType ClassType::* | निर्दिष्ट वस्तु की नॉन-स्टैटिक मेथड का पॉइंटर |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | वह ऑब्जेक्ट का शेयर्ड पॉइंटर जिसका मेथड संग्रह में जोड़ना है |

### वापसी मान

स्वयं का संदर्भ

## संबंधित देखें

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* मेथड [MulticastDelegate](../multicastdelegate/)
* क्लास [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* नामस्थान [System](../../)
* Library [Aspose.Slides](../../../)