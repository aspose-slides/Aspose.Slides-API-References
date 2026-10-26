---
title: LookupNamespace()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Résout un préfixe d'espace de noms dans la portée de l'élément actuel.
type: docs
weight: 612
url: /fr/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) méthode

Résout un préfixe d'espace de noms dans la portée de l'élément actuel.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Le préfixe dont vous voulez résoudre l'URI d'espace de noms. Pour correspondre à l'espace de noms par défaut, passez une chaîne vide. Cette chaîne n'a pas besoin d'être atomisée. |

### Valeur de retour

L'URI d'espace de noms auquel le préfixe correspond ou **nullptr** si aucun préfixe correspondant n'est trouvé.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)