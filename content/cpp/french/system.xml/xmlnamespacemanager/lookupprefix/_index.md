---
title: LookupPrefix()
second_title: Référence API Aspose.Slides pour C++
description: Trouve le préfixe déclaré pour l'URI d'espace de noms fourni.
type: docs
weight: 131
url: /fr/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) méthode


Recherche le préfixe déclaré pour l'URI d'espace de noms fourni.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | L'espace de noms à résoudre pour le préfixe. |

### Valeur de retour

Le préfixe correspondant. S'il n'existe aucun préfixe mappé, la méthode renvoie [String::Empty](../../../system/string/empty/). Si une valeur nulle est fournie, **nullptr** est renvoyé.

## Voir aussi

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)