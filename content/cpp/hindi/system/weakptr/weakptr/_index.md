---
title: WeakPtr()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: नल पॉइंटर बनाता है।
type: docs
weight: 1
url: /hi/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) कन्स्ट्रक्टर

नल पॉइंटर बनाता है।

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```
## WeakPtr::WeakPtr(Pointee_ *) कन्स्ट्रक्टर

दिए गए ऑब्जेक्ट के लिए कमजोर पॉइंटर बनाता है।

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) जिससे कमजोर पॉइंटर बनाया जाता है। |

## WeakPtr::WeakPtr(const SmartPtr_\&) कन्स्ट्रक्टर

वही पॉइंटर जिस पर ptr संकेत करता है, उसे संदर्भित करता हुआ कमजोर पॉइंटर बनाता है।

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | पॉइंटर जिससे प्वाइंटेड मान को कॉपी किया जाता है। |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) कन्स्ट्रक्टर

वही पॉइंटर जिस पर x संकेत करता है, उसे संदर्भित करता हुआ कमजोर पॉइंटर बनाता है।

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | स्रोत पॉइंटर का प्वाइंटिड टाइप। |

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | पॉइंटर जिससे प्वाइंटेड मान को कॉपी किया जाता है। |

## WeakPtr::WeakPtr(const WeakPtr_\&) कन्स्ट्रक्टर

कमजोर पॉइंटर को कॉपी-कन्स्ट्रक्ट करता है।

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | पॉइंटर जिससे प्वाइंटेड मान को कॉपी किया जाता है। |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) कन्स्ट्रक्टर

कमजोर पॉइंटर को कॉपी-कन्स्ट्रक्ट करता है।

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | स्रोत प्वाइंटिड टाइप। |

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | पॉइंटर जिससे प्वाइंटेड मान को कॉपी किया जाता है। |

## WeakPtr::WeakPtr(SmartPtr_\&&) कन्स्ट्रक्टर

कमजोर पॉइंटर को मूव-कन्स्ट्रक्ट करता है।

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | पॉइंटर जिससे प्वाइंटेड मान को मूव किया जाता है। |

## See Also

* टाइपडिफ [Pointee_](../../smartptr/pointee_/)
* टाइपडिफ [SmartPtr_](../../smartptr/smartptr_/)
* टाइपडिफ [WeakPtr_](../weakptr_/)
* क्लास [WeakPtr](../)
* क्लास [SmartPtr](../../smartptr/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)