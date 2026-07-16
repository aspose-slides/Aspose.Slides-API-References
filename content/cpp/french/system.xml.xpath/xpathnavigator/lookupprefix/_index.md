---
title: LookupPrefix()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le préfixe déclaré pour l'URI d'espace de noms spécifié.
type: docs
weight: 417
url: /fr/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) méthode

Renvoie le préfixe déclaré pour l'URI d'espace de noms spécifié.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | L'URI d'espace de noms à résoudre pour le préfixe. |

### Valeur de retour

Un [String](../../../system/string/) qui contient le préfixe d'espace de noms attribué à l'URI d'espace de noms spécifié ; sinon, [String::Empty](../../../system/string/empty/) si aucun préfixe n'est attribué à l'URI d'espace de noms spécifié. Le [String](../../../system/string/) retourné est atomisé.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)