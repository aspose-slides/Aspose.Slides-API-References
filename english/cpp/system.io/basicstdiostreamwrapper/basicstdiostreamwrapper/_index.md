---
title: BasicSTDIOStreamWrapper()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of the BasicSTDIOStreamWrapper.
type: docs
weight: 14
url: /cpp/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/), [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)) constructor


Constructs a new instance of the [BasicSTDIOStreamWrapper](../).

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | The reference to the stream |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Wrapping mode |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | Position that will prefer as read and write position, if they are different |

## See Also

* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const [BasicSTDIOStreamWrapper](../)\&) constructor


Copy constructor. Deleted.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## See Also

* Class [BasicSTDIOStreamWrapper](../)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
