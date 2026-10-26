---
title: CloneNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un duplicata de ce nœud.
type: docs
weight: 118
url: /fr/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) méthode

Crée un duplicata de ce nœud.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** pour cloner récursivement le sous-arbre sous le nœud spécifié; **false** pour cloner uniquement le nœud lui-même. Pour les nœuds de type document, le nœud cloné comprend toujours le sous-arbre, quel que soit le paramètre. |

### Valeur de retour

Le nœud cloné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlDocumentType](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)