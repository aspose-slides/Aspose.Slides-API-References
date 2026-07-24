---
title: CreatePortion()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen leeren Textabschnitt.
type: docs
weight: 1
url: /de/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() Methode

Erstellt einen leeren Textabschnitt.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### Rückgabewert

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) Methode

Erstellt einen Textabschnitt aus einem angegebenen String.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Rückgabewert

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) Methode

Erstellt einen Abschnitt unter Verwendung der angegebenen Abschnittsdaten.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Ein zu verwendender Abschnitt. |

### Rückgabewert

[Portion](../../portion/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPortion](../../iportion/)
* Klasse [IPortionFactory](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)