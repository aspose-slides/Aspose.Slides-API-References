---
title: CreatePortion()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří prázdnou textovou část.
type: docs
weight: 1
url: /cs/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() metoda

Vytvoří prázdnou textovou část.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Návratová hodnota

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) metoda

Vytvoří textovou část ze zadaného řetězce.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Návratová hodnota

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metoda

Vytvoří část za použití zadaných dat části.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Část k použití. |

### Návratová hodnota

[Portion](../../portion/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPortion](../../iportion/)
* Třída [PortionFactory](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)