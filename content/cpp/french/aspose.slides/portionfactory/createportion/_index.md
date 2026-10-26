---
title: CreatePortion()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une portion de texte vide.
type: docs
weight: 1
url: /fr/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() méthode

Crée une portion de texte vide.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Valeur de retour

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) méthode

Crée une portion de texte à partir de la chaîne spécifiée.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Chaîne. |

### Valeur de retour

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) méthode

Crée une portion en utilisant les données d'une portion spécifiée.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Une portion à utiliser. |

### Valeur de retour

[Portion](../../portion/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortion](../../iportion/)
* Classe [PortionFactory](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)