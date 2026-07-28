---
title: DbProviderFactories
second_title: Aspose.Slides dla C++ – odniesienie API
description: "API do pobierania fabryk dostawców DB. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania jej funkcjom jako argument."
type: docs
weight: 53
url: /pl/system.data.common/dbproviderfactories/
---
## DbProviderFactories klasa


API do pobierania fabryk dostawców DB. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonania i/lub awarie asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argumentu.

```cpp
class DbProviderFactories
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Pobiera fabrykę dostawcy DB według nazwy. |
## Zobacz także

* Przestrzeń nazw [System::Data::Common](../)
* Biblioteka [Aspose.Slides](../../)