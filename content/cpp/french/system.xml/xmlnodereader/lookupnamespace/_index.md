---
title: LookupNamespace()
second_title: Référence API Aspose.Slides pour C++
description: Résout un préfixe d'espace de noms dans la portée de l'élément actuel.
type: docs
weight: 404
url: /fr/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) méthode


Résout un préfixe d'espace de noms dans la portée de l'élément actuel.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Le préfixe dont vous souhaitez résoudre l'URI de l'espace de noms. Pour correspondre à l'espace de noms par défaut, passez une chaîne vide. Cette chaîne n'a pas besoin d'être atomisée. |

### Valeur de retour

L'URI de l'espace de noms auquel le préfixe correspond ou **nullptr** si aucun préfixe correspondant n'est trouvé.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)