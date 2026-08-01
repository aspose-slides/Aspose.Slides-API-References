---
title: CreatePortion()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt een lege tekstdeler.
type: docs
weight: 1
url: /nl/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() method

Creëert een lege tekstdeler.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### Retourwaarde

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) method

Creëert een tekstdeler van de opgegeven string.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Retourwaarde

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) method

Creëert een gedeelte met behulp van gespecificeerde gedeeltegegevens.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Een gedeelte om te gebruiken. |

### Retourwaarde

[Portion](../../portion/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPortion](../../iportion/)
* Klasse [IPortionFactory](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)