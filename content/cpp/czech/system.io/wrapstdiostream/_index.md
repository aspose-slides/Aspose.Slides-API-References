---
title: WrapSTDIOStream()
second_title: Aspose.Slides pro C++ referenci API
description: "Obalová funkce pro proudy podobné std::basic_istream."
type: docs
weight: 469
url: /cs/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function


Obalová funkce pro proudy podobné std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | proud podobný std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | režim balení |

### Návratová hodnota

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function


Obalová funkce pro proudy podobné std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | proud podobný std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | režim balení |

### Návratová hodnota

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) function


Obalová funkce pro proudy podobné std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | proud podobný std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | režim balení |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Pozice, která bude preferována jako pozice pro čtení a zápis, pokud jsou odlišné |

### Návratová hodnota

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## Viz také

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)