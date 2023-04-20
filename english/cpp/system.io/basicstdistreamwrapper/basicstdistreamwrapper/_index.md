---
title: BasicSTDIStreamWrapper()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of the BasicSTDIStreamWrapper.
type: docs
weight: 14
url: /cpp/system.io/basicstdistreamwrapper/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) constructor


Constructs a new instance of the [BasicSTDIStreamWrapper](../).

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(std::basic_istream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | std::basic_istream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | The reference to the stream |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Wrapping mode |

## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper\&) constructor


Copy constructor. Deleted.

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper &)=delete
```

## See Also

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)