---
title: BasicSTDIOStreamWrapper()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową instancję BasicSTDIOStreamWrapper.
type: docs
weight: 14
url: /pl/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) konstruktor

Tworzy nową instancję [BasicSTDIOStreamWrapper](../).

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | Referencja do strumienia |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Tryb opakowywania |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | Pozycja, która będzie preferowana jako pozycja odczytu i zapisu, jeśli są różne |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) konstruktor

Konstruktor kopiujący. Usunięty.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## Zobacz także

* Wyliczenie [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Wyliczenie [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* Definicja typu [char_type](../../stdiostreamwrapperbase/char_type/)
* Definicja typu [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Klasa [BasicSTDIOStreamWrapper](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)