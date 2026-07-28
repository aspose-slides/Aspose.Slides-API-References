---
title: CreatePortion()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy pustą część tekstową.
type: docs
weight: 1
url: /pl/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() metoda


Tworzy pustą część tekstową.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```


### Wartość zwracana

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) metoda


Tworzy część tekstową z określonego ciągu znaków.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Ciąg znaków. |

### Wartość zwracana

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metoda


Tworzy część przy użyciu określonych danych części.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Część do użycia. |

### Wartość zwracana

[Portion](../../portion/).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IPortion](../../iportion/)
* Klasa [PortionFactory](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)