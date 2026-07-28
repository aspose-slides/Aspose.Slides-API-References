---
title: WrapSTDIOStream()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Funkcja opakowująca dla strumieni podobnych do std::basic_istream."
type: docs
weight: 469
url: /pl/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) funkcja

Funkcja opakowująca dla strumieni podobnych do std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | strumień podobny do std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Tryb opakowania |

### Wartość zwracana

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) opakowanie

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) funkcja


Funkcja opakowująca dla strumieni podobnych do std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | strumień podobny do std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Tryb opakowania |

### Wartość zwracana

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) opakowanie

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) funkcja


Funkcja opakowująca dla strumieni podobnych do std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | strumień podobny do std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Tryb opakowania |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Pozycja, która będzie preferowana jako pozycja odczytu i zapisu, jeśli są różne |

### Wartość zwracana

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) opakowanie

## Zobacz także

* Wyliczenie [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Wyliczenie [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Definicja typu [SharedPtr](../../system/sharedptr/)
* Klasa [Stream](../stream/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)