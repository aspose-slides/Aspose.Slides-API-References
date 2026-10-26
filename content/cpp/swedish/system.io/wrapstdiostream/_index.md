---
title: WrapSTDIOStream()
second_title: Aspose.Slides för C++ API-referens
description: "Wrapper-funktion för std::basic_istream-liknande strömmar."
type: docs
weight: 469
url: /sv/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) funktion

Wrapper-funktion för std::basic_istream-liknande strömmar.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream-liknande stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping mode |

### Returvärde

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) funktion

Wrapper-funktion för std::basic_ostream-liknande strömmar.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream-liknande stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping mode |

### Returvärde

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) funktion

Wrapper-funktion för std::basic_iostream-liknande strömmar.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream-liknande stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping mode |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Position som föredras som läs- och skrivposition, om de är olika |

### Returvärde

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## Se även

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typdef [SharedPtr](../../system/sharedptr/)
* Klass [Stream](../stream/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)