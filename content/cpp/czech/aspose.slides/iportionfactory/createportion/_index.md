---
title: CreatePortion()
second_title: Aspose.Slides pro C++ referenci API
description: Vytvoří prázdnou textovou část.
type: docs
weight: 1
url: /cs/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() metoda

Vytvoří prázdnou část textu.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### Návratová hodnota

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) metoda

Vytvoří část textu ze zadaného řetězce.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Návratová hodnota

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metoda

Vytvoří část s použitím specifikovaných dat části.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | A portion to use. |

### Návratová hodnota

[Portion](../../portion/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPortion](../../iportion/)
* Třída [IPortionFactory](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)