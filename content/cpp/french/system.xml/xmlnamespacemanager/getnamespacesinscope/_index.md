---
title: GetNamespacesInScope()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une collection de noms d'espace de noms indexés par préfixe pouvant être utilisée pour énumérer les espaces de noms actuellement en vigueur.
type: docs
weight: 105
url: /fr/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) method


Renvoie une collection de noms d’espace de noms indexés par préfixe pouvant être utilisée pour énumérer les espaces de noms actuellement en vigueur.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Une valeur d’énumération qui spécifie le type de nœuds d’espace de noms à renvoyer. |

### Valeur de retour

Une collection de paires espace de noms / préfixe actuellement en vigueur.

## Voir aussi

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)