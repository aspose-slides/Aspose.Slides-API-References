---
title: CreatePortion()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine leere Textportion.
type: docs
weight: 1
url: /de/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() Methode

Erstellt eine leere Textportion.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Rückgabewert

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) Methode

Erstellt eine Textportion aus einer angegebenen Zeichenkette.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Rückgabewert

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) Methode

Erstellt eine Portion unter Verwendung von angegebenen Portionsdaten.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Eine Portion zur Verwendung. |

### Rückgabewert

[Portion](../../portion/).

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPortion](../../iportion/)
* Klasse [PortionFactory](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)