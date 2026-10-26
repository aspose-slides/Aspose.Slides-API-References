---
title: LoadingStreamBehavior
second_title: Aspose.Slides pro C++ – reference API
description: "System::IO::Stream předaný metodě je považován za binární velký objekt (BLOB) (viz popis IBlobManagementOptions). Hodnoty tohoto výčtu určují, jak má být System::IO::Stream zacházeno, když je předán metodě. V závislosti na požadavcích lze učinit různá rozhodnutí, aby se zajistilo nejefektivnější chování."
type: docs
weight: 6735
url: /cs/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

The [System::IO::Stream](../../system.io/stream/) passed to a method is considered as a Binary Large Object (BLOB) (see [IBlobManagementOptions](../iblobmanagementoptions/) description). Values of this enumeration identify how the [System::IO::Stream](../../system.io/stream/) should be treated when it passed to the method. Depending on the requirements, different decisions could be made to provide the most efficient behavior.

```cpp
enum class LoadingStreamBehavior
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Stream bude čten až do konce a poté uvolněn – tj. bude zaručeno, že tento stream nebude v budoucnu používán instancí [IPresentation](../ipresentation/). Může být uzavřen klientským kódem nebo použit jiným způsobem. |
| KeepLocked | 1 | Stream bude uzamčen uvnitř objektu [IPresentation](../ipresentation/), tj. vlastnictví streamu bude převedeno. Objekt [IPresentation](../ipresentation/) bude zodpovědný za správné uvolnění streamu, když bude tento objekt sám uvolněn. Toto chování je mimořádně užitečné, když potřebujete serializovat velký BLOB soubor (např. velké video nebo audio – viz [IBlobManagementOptions](../iblobmanagementoptions/) popis) a chcete zabránit načítání tohoto souboru do paměti nebo jiným problémům s výkonem. Můžete jednoduše otevřít [System::IO::FileStream](../../system.io/filestream/) pro tento soubor a předat jej metodě, přičemž zvolíte [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## Viz také

* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)