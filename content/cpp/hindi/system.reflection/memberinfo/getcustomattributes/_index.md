---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए प्रकार पर लागू सभी कस्टम एट्रिब्यूट्स को दर्शाने वाले वस्तुओं की एक एरे लौटाता है।
type: docs
weight: 66
url: /hi/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const method

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए प्रकार पर लागू सभी कस्टम एट्रिब्यूट्स को दर्शाने वाले ऑब्जेक्ट्स की एक एरे लौटाता है।

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | खोजने के लिये एट्रिब्यूट का प्रकार। |
| inherit | **bool** | क्या विरासत में मिली एट्रिब्यूट्स को भी जांचना है। |

## MemberInfo::GetCustomAttributes(bool) const method

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए प्रकार पर लागू सभी कस्टम एट्रिब्यूट्स को दर्शाने वाले ऑब्जेक्ट्स की एक एरे लौटाता है।

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| inherit | **bool** | क्या विरासत में मिली एट्रिब्यूट्स को भी जांचना है। |

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)