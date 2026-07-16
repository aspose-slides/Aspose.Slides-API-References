---
title: CloneNode()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Crée un duplicata de ce nœud.
type: docs
weight: 79
url: /fr/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) méthode


Crée un duplicata de ce nœud.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** pour cloner récursivement le sous-arbre sous le nœud spécifié ; **false** pour cloner uniquement le nœud lui-même. Pour les nœuds d'espaces blancs significatifs, le nœud cloné inclut toujours la valeur de données, quel que soit le réglage du paramètre. |

### Valeur de retour

Le nœud cloné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlSignificantWhitespace](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)