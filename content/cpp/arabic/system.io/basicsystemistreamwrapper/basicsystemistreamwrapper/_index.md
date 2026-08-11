---
title: BasicSystemIStreamWrapper()
second_title: مرجع API Aspose.Slides للغة C++
description: إنشاء مثيل جديد من BasicSystemIStreamWrapper.
type: docs
weight: 1
url: /ar/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) منشئ


ينشئ مثيلًا جديدًا من [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | المؤشر إلى التيار |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | وضع التغليف |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) منشئ


منشئ النسخ. محذوف.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) منشئ


منشئ النقل.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) للنقل |

## انظر أيضًا

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BasicSystemIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)