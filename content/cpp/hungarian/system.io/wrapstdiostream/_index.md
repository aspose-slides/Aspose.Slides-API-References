---
title: WrapSTDIOStream()
second_title: Aspose.Slides C++ API-referencia
description: "Csomagoló függvény a std::basic_istream-szerű adatfolyamokhoz."
type: docs
weight: 469
url: /hu/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) függvény


Csomagoló függvény a std::basic_istream-szerű adatfolyamokhoz.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream-szerű adatfolyam |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Csomagolási mód |

### Visszatérési érték

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) csomagoló

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) függvény


Csomagoló függvény a std::basic_ostream-szerű adatfolyamokhoz.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream-szerű adatfolyam |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Csomagolási mód |

### Visszatérési érték

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) csomagoló

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) függvény


Csomagoló függvény a std::basic_iostream-szerű adatfolyamokhoz.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream-szerű adatfolyam |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Csomagolási mód |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Pozíció, amelyet olvasási és írási pozícióként részesítenek előnyben, ha különbözőek |

### Visszatérési érték

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) csomagoló

## Lásd még

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)