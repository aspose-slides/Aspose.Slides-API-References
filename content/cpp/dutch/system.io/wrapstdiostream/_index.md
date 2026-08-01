---
title: WrapSTDIOStream()
second_title: Aspose.Slides voor C++ API-referentie
description: "Wrapper-functie voor streams die op std::basic_istream lijken."
type: docs
weight: 469
url: /nl/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) functie

Wrapper-functie voor streams die op std::basic_istream lijken.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream-achtige stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping mode |

### Retourwaarde

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) functie

Wrapper-functie voor streams die op std::basic_ostream lijken.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream-achtige stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping mode |

### Retourwaarde

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) functie

Wrapper-functie voor streams die op std::basic_iostream lijken.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream-achtige stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Wrapping mode |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Positie die wordt geprefereerd als lees- en schrijfpunt, als deze verschillend zijn |

### Retourwaarde

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## Zie ook

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [Stream](../stream/)
* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)