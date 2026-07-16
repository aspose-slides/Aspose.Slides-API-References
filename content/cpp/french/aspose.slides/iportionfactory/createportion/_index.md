---
title: CreatePortion()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une portion de texte vide.
type: docs
weight: 1
url: /fr/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() méthode


Crée une portion de texte vide.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### Valeur de retour

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) méthode


Crée une portion de texte à partir de la chaîne spécifiée.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Valeur de retour

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) méthode


Crée une portion en utilisant les données d’une portion spécifiée.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Une portion à utiliser. |

### Valeur de retour

[Portion](../../portion/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [IPortionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)