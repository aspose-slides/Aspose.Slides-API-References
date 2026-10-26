---
title: OperatingSystem
second_title: Aspose.Slides dla C++ Odniesienie API
description: "Reprezentuje konkretny system operacyjny i zapewnia informacje o nim. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go do funkcji jako argument."
type: docs
weight: 1171
url: /pl/system/operatingsystem/
---
## OperatingSystem klasa

Reprezentuje konkretny system operacyjny i zapewnia informacje o nim. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../smartptr/) i używaj tego wskaźnika do przekazywania go do funkcji jako argument.

```cpp
class OperatingSystem
```

## Metody

| Metoda | Opis |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Zwraca identyfikator platformy systemu operacyjnego reprezentowanego przez bieżący obiekt. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Zwraca nazwę pakietu serwisowego systemu operacyjnego reprezentowanego przez bieżący obiekt. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Zwraca stałe odwołanie do obiektu [Version](../version/) reprezentującego wersję systemu operacyjnego reprezentowanego przez bieżący obiekt. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Zwraca łańcuch znaków reprezentujący wersję systemu operacyjnego reprezentowanego przez bieżący obiekt. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Wskazuje, czy bieżąca aplikacja działa na FreeBSD. |
| static **bool** [IsLinux](./islinux/)() | Wskazuje, czy bieżąca aplikacja działa na Linux. |
| static **bool** [IsMacOS](./ismacos/)() | Wskazuje, czy bieżąca aplikacja działa na MacOS. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Wskazuje, czy bieżąca aplikacja działa na określonej platformie. |
| static **bool** [IsWindows](./iswindows/)() | Wskazuje, czy bieżąca aplikacja działa na [Windows](../../system.windows/). |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Tworzy instancję reprezentującą system operacyjny określony jako konkretny identyfikator platformy i wersja. |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Tworzy instancję reprezentującą system operacyjny określony jako konkretny identyfikator platformy, wersja oraz pakiet serwisowy. |
| [String](../string/) [ToString](./tostring/)() const | Zwraca łańcuch znaków reprezentujący wersję systemu operacyjnego reprezentowanego przez bieżący obiekt. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)