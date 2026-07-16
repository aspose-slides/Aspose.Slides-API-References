---
title: Supports()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si l'implémentation du DOM implémente une fonctionnalité spécifique.
type: docs
weight: 482
url: /fr/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) méthode

Teste si l'implémentation du DOM implémente une fonctionnalité spécifique.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| feature | [String](../../../system/string/) | Le nom du package de la fonctionnalité à tester. Ce nom n'est pas sensible à la casse. |
| version | [String](../../../system/string/) | Le numéro de version du nom du package à tester. Si la version n'est pas spécifiée (null), le support de n'importe quelle version de la fonctionnalité conduit la méthode à retourner true. |

### Valeur de retour

**true** si la fonctionnalité est implémentée dans la version spécifiée ; sinon, **false**.

## Remarques

Le tableau suivant décrit les combinaisons qui renvoient **true**. 

| Fonctionnalité | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)