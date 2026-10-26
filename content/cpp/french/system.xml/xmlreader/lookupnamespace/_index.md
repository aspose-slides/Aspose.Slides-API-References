---
title: LookupNamespace()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est redéfinie dans une classe dérivée, résout un préfixe d'espace de noms dans la portée de l'élément courant.
type: docs
weight: 729
url: /fr/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) méthode


Lorsqu'elle est redéfinie dans une classe dérivée, résout un préfixe d'espace de noms dans la portée de l'élément courant.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Le préfixe dont vous souhaitez résoudre l'URI d'espace de noms. Pour correspondre à l'espace de noms par défaut, passez une chaîne vide. |

### Valeur de retour

L'URI d'espace de noms vers lequel le préfixe pointe ou **nullptr** si aucun préfixe correspondant n'est trouvé.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)