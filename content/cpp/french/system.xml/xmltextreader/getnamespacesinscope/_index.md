---
title: GetNamespacesInScope()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie une collection qui contient tous les espaces de noms actuellement en portée.
type: docs
weight: 716
url: /fr/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) méthode

Retourne une collection qui contient tous les espaces de noms actuellement en portée.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Une valeur XmlNamespaceScope qui spécifie le type de nœuds d'espace de noms à retourner. |

### Valeur de retour

Un objet IDictionary qui contient tous les espaces de noms en cours de portée. Si le lecteur n'est pas positionné sur un élément, un dictionnaire vide (aucun espace de noms) est renvoyé.

## Voir aussi

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)