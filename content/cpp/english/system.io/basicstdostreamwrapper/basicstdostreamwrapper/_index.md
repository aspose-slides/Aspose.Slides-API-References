---
title: BasicSTDOStreamWrapper()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of the BasicSTDOStreamWrapper.
type: docs
weight: 14
url: /system.io/basicstdostreamwrapper/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) constructor


Constructs a new instance of the [BasicSTDOStreamWrapper](../).

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(std::basic_ostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | std::basic_ostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | The reference to the stream |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Wrapping mode |

## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper\&) constructor


Copy constructor. Deleted.

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper &)=delete
```

## See Also

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)