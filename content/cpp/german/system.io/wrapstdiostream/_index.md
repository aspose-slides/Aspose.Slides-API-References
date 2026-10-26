---
title: WrapSTDIOStream()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wrapper-Funktion für std::basic_istream-ähnliche Streams."
type: docs
weight: 469
url: /de/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function

Wrapper-Funktion für std::basic_istream-ähnliche Streams.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream-ähnlicher Stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping-Modus |

### Rückgabewert

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) Wrapper

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function

Wrapper-Funktion für std::basic_ostream-ähnliche Streams.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream-ähnlicher Stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping-Modus |

### Rückgabewert

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) Wrapper

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) function

Wrapper-Funktion für std::basic_iostream-ähnliche Streams.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream-ähnlicher Stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping-Modus |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Position, die als Lese- und Schreibposition bevorzugt wird, falls sie unterschiedlich sind |

### Rückgabewert

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) Wrapper

## Siehe auch

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)