---
title: HasFeature()
second_title: Référence de l'API Aspose.Slides for C++
description: Teste si l'implémentation du Document Object Model (DOM) prend en charge une fonctionnalité spécifique.
type: docs
weight: 14
url: /fr/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) method

Vérifie si l'implémentation du Document [Object](../../../system/object/) modèle (DOM) prend en charge une fonctionnalité spécifique.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | Le nom du paquet de la fonctionnalité à tester. Ce nom n'est pas sensible à la casse. |
| strVersion | const [String](../../../system/string/)\& | C’est le numéro de version du nom du paquet à tester. Si la version n’est pas spécifiée (**nullptr**), le support de n’importe quelle version de la fonctionnalité entraîne le retour **true** de la méthode. |

### Valeur de retour

**true** si la fonctionnalité est implémentée dans la version spécifiée ; sinon, **false**.

## Remarques

Le tableau suivant montre les combinaisons qui font que **HasFeature** renvoie **true**. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlImplementation](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)