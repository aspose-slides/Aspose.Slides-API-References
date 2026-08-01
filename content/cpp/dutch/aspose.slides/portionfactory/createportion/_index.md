---
title: CreatePortion()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een leeg tekstgedeelte aan.
type: docs
weight: 1
url: /nl/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() methode


Maakt een lege tekstgedeelte aan.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```


### Retourwaarde

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) methode


Maakt een tekstgedeelte aan van een opgegeven string.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Retourwaarde

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) methode


Maakt een gedeelte aan met behulp van gespecificeerde gedeeltegegevens.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
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
* Klasse [PortionFactory](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)