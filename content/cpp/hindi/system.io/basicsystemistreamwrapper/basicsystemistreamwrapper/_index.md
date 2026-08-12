---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: BasicSystemIStreamWrapper का नया उदाहरण बनाता है।
type: docs
weight: 1
url: /hi/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) कंस्ट्रक्टर


एक नया उदाहरण बनाता है [BasicSystemIStreamWrapper](../) का।

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | स्ट्रीम का पॉइंटर |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | रैपिंग मोड |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) कंस्ट्रक्टर


कॉपी कंस्ट्रक्टर। हटा दिया गया।

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) कंस्ट्रक्टर


मूव कंस्ट्रक्टर।

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) को मूव किया जाना है |

## देखें

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Stream](../../stream/)
* क्लास [BasicSystemIStreamWrapper](../)
* नेमस्पेस [System::IO](../../)
* Library [Aspose.Slides](../../../)