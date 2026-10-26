---
title: OperatingSystem()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy instancję reprezentującą system operacyjny określony za pomocą konkretnego identyfikatora platformy i wersji.
type: docs
weight: 1
url: /pl/system/operatingsystem/operatingsystem/
---
## OperatingSystem::OperatingSystem(PlatformID, const Version\&) konstruktor

Tworzy instancję reprezentującą system operacyjny określony jako konkretny identyfikator platformy i wersja.

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | Identyfikator platformy systemu operacyjnego, który ma być reprezentowany przez tworzony obiekt |
| version | const [Version](../../version/)\& | Wersja systemu operacyjnego, który ma być reprezentowany przez tworzony obiekt |

## OperatingSystem::OperatingSystem(PlatformID, const Version\&, const String\&) konstruktor

Tworzy instancję reprezentującą system operacyjny określony jako konkretny identyfikator platformy, wersja i pakiet serwisowy.

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version, const String &service_pack)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | Identyfikator platformy systemu operacyjnego, który ma być reprezentowany przez tworzony obiekt |
| version | const [Version](../../version/)\& | Wersja systemu operacyjnego, który ma być reprezentowany przez tworzony obiekt |
| service_pack | const [String](../../string/)\& | Nazwa pakietu serwisowego systemu operacyjnego, który ma być reprezentowany przez tworzony obiekt |

## Zobacz także

* Enum [PlatformID](../../platformid/)
* Klasa [Version](../../version/)
* Klasa [OperatingSystem](../)
* Klasa [String](../../string/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)