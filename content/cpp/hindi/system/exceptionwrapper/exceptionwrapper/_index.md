---
title: ExceptionWrapper()
second_title: Aspose.Slides for C++ API संदर्भ
description: ExceptionWrapper क्लास की एक null-instance बनाता है जो किसी भी अपवाद का प्रतिनिधित्व नहीं करता।
type: docs
weight: 14
url: /hi/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) constructor


एक null-instance बनाता है [ExceptionWrapper](../) वर्ग का जो किसी अपवाद का प्रतिनिधित्व नहीं करता।

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) constructor


[ExceptionWrapper](../) वर्ग का एक instance बनाता है जिसमें पास किया गया पॉइंटर शामिल है।

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Smart pointer to the instance of Exception class. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) constructor


कॉपी कंस्ट्रक्टर।

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Other instance of wrapper class that must be copied. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) constructor


मूव कंस्ट्रक्टर।

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Other instance of wrapper class that must be moved. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) constructor


एक कंस्ट्रक्टर जो पैरामीटर को Exception वर्ग के कंस्ट्रक्टर्स को फ़ॉरवर्ड करता है और एक स्मार्ट पॉइंटर बनाता है जो नए Exception वर्ग की instance को रखता है।

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## देखें

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)