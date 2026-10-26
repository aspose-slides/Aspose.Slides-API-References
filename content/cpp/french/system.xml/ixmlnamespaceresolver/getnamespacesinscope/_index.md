---
title: GetNamespacesInScope()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une collection des mappages préfixe-espace de noms définis qui sont actuellement en portée.
type: docs
weight: 1
url: /fr/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) méthode

Renvoie une collection des mappages préfixe-espace de noms définis qui sont actuellement en portée.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Une valeur XmlNamespaceScope qui spécifie le type de nœuds d'espace de noms à renvoyer. |

### Valeur de retour

Une collection IDictionary qui contient les espaces de noms actuellement en portée.

## Voir aussi

* Enumération [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [IXmlNamespaceResolver](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)