---
title: LookupNamespace()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie l'URI de l'espace de noms pour le préfixe spécifié.
type: docs
weight: 118
url: /fr/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) méthode

Renvoie l'URI d'espace de noms pour le préfixe spécifié.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Le préfixe dont vous souhaitez résoudre l'URI d'espace de noms. Pour correspondre à l'espace de noms par défaut, passez [String::Empty](../../../system/string/empty/). |

### Valeur de retour

L'URI d'espace de noms pour **prefix** ou **nullptr** s'il n'existe aucun espace de noms mappé. La chaîne renvoyée est atomisée. Pour plus d'informations sur les chaînes atomisées, voir la classe [XmlNameTable](../../xmlnametable/).

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)