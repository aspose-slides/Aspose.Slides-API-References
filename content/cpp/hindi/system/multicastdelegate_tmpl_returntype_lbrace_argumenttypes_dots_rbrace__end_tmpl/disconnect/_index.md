---
title: disconnect()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट प्रतिनिधि को प्रतिनिधि संग्रह से हटा देता है।
type: docs
weight: 170
url: /hi/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) विधि


निर्दिष्ट प्रतिनिधि को प्रतिनिधि संग्रह से हटा देता है।

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [Callback](../callback/) | संग्रह से हटाने हेतु प्रतिनिधि |

### रिटर्न मान

स्वयं का संदर्भ

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) विधि


निर्दिष्ट वस्तु के निर्दिष्ट गैर-स्थैतिक मेथड को प्रतिनिधि संग्रह से हटा देता है।

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### टेम्पलेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| MemberType | प्रतिनिधि संग्रह से हटाए जाने वाले गैर-स्थैतिक मेथड का प्रकार |
| ClassType | प्रतिनिधि संग्रह से हटाए जाने वाले ऑब्जेक्ट मेथड का प्रकार |

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| member | MemberType ClassType::* | निर्दिष्ट वस्तु के गैर-स्थैतिक मेथड का एक पॉइंटर |
| obj | ClassType * | प्रतिनिधि संग्रह से हटाने हेतु ऑब्जेक्ट सदस्य मेथड का एक पॉइंटर |

### रिटर्न मान

स्वयं का संदर्भ

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) विधि


निर्दिष्ट वस्तु के निर्दिष्ट गैर-स्थैतिक मेथड को प्रतिनिधि संग्रह से हटा देता है।

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### टेम्पलेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| MemberType | प्रतिनिधि संग्रह से हटाए जाने वाले गैर-स्थैतिक मेथड का प्रकार |
| ClassType | प्रतिनिधि संग्रह से हटाए जाने वाले ऑब्जेक्ट मेथड का प्रकार |

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| member | MemberType ClassType::* | निर्दिष्ट वस्तु के गैर-स्थैतिक मेथड का एक पॉइंटर |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | प्रतिनिधि संग्रह से हटाने हेतु ऑब्जेक्ट सदस्य मेथड का एक साझा पॉइंटर |

### रिटर्न मान

स्वयं का संदर्भ

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) विधि


निर्दिष्ट MulticastDelegate ऑब्जेक्ट को प्रतिनिधि संग्रह से हटा देता है।

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | प्रतिनिधि संग्रह से हटाने हेतु MulticastDelegate क्लास का एक उदाहरण |

### रिटर्न मान

स्वयं का संदर्भ

## देखें

* टाइपडिफ [Callback](../callback/)
* टाइपडिफ [SharedPtr](../../sharedptr/)
* विधि [MulticastDelegate](../multicastdelegate/)
* क्लास [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)