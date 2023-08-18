---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of the BasicSystemOStreamWrapper.
type: docs
weight: 1
url: /system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructor


Constructs a new instance of the [BasicSystemOStreamWrapper](../).

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | The pointer to the stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Wrapping mode |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) constructor


Copy constructor. Deleted.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) constructor


Move constructor.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) to be move |

## See Also

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BasicSystemOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)