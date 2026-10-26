---
title: BasicSTDOStreamWrapper()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert eine neue Instanz von BasicSTDOStreamWrapper.
type: docs
weight: 14
url: /de/system.io/basicstdostreamwrapper/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) Konstruktor


Constructs a new instance of the [BasicSTDOStreamWrapper](../).

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(std::basic_ostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | std::basic_ostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | Die Referenz auf den Stream |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Umhüllungsmodus |

## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper\&) Konstruktor


Kopierkonstruktor. Gelöscht.

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper &)=delete
```

## Siehe auch

* Aufzählung [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Typdefinition [char_type](../../stdiostreamwrapperbase/char_type/)
* Typdefinition [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Klasse [BasicSTDOStreamWrapper](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)