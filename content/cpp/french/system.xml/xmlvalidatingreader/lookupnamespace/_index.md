---
title: LookupNamespace()
second_title: Référence API Aspose.Slides pour C++
description: Résout un préfixe d'espace de noms dans la portée de l'élément actuel.
type: docs
weight: 547
url: /fr/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) méthode


Résout un préfixe d'espace de noms dans la portée de l'élément actuel.

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Le préfixe dont vous voulez résoudre l'Uniform Resource Identifier (URI) de l'espace de noms. Pour correspondre à l'espace de noms par défaut, passez une chaîne vide. |

### Valeur de retour

L'URI de l'espace de noms vers lequel le préfixe se mappe ou **nullptr** si aucun préfixe correspondant n'est trouvé.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlValidatingReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)