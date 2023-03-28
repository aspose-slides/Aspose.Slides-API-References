---
title: WrapSTDIOStream()
second_title: Aspose.Slides for C++ API Reference
description: "Wrapper function for std::basic_istream-like streams."
type: docs
weight: 456
url: /cpp/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) function


Wrapper function for std::basic_istream-like streams.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream-like stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping mode |

### Return Value

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)
## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) function


Wrapper function for std::basic_ostream-like streams.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream-like stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping mode |

### Return Value

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)
## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/), [STDIOStreamPositionPreference](../stdiostreampositionpreference/)) function


Wrapper function for std::basic_iostream-like streams.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream-like stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping mode |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Position that will prefer as read and write position, if they are different |

### Return Value

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)
