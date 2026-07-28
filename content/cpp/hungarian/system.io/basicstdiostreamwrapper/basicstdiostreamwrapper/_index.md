---
title: BasicSTDIOStreamWrapper()
second_title: Aspose.Slides for C++ API hivatkozás
description: Új példányt hoz létre a BasicSTDIOStreamWrapper osztályból.
type: docs
weight: 14
url: /hu/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) konstruktor


Új példányt hoz létre a [BasicSTDIOStreamWrapper](../).

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | A stream referenciája |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Befoglalási mód |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | Pozíció, amelyet olvasási és írási helynek részesít előnyben, ha eltérőek |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) konstruktor


Másoló konstruktor. Törölve.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## Lásd még

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Osztály [BasicSTDIOStreamWrapper](../)
* Névtér [System::IO](../../)
* Library [Aspose.Slides](../../../)