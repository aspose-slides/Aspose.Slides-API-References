---
title: LookupNamespace()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie l'URI de l'espace de noms pour le préfixe spécifié.
type: docs
weight: 404
url: /fr/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) method

Renvoie l'URI de l'espace de noms pour le préfixe spécifié.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | le préfixe dont vous souhaitez résoudre l'URI de l'espace de noms. Pour correspondre à l'espace de noms par défaut, passez [String::Empty](../../../system/string/empty/). |

### Valeur de retour

Un [String](../../../system/string/) qui contient l'URI de l'espace de noms assigné au préfixe d'espace de noms spécifié ; **nullptr** si aucun URI d'espace de noms n'est assigné au préfixe spécifié. Le [String](../../../system/string/) renvoyé est atomisé.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)