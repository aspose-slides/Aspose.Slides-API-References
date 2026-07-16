---
title: CloneNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une copie de ce nœud.
type: docs
weight: 196
url: /fr/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode(bool) méthode

Crée une copie de ce nœud.

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** pour cloner récursivement le sous-arbre sous le nœud spécifié ; **false** pour cloner uniquement le nœud lui-même (et ses attributs si le nœud est un [XmlElement](../)). |

### Valeur de retour

Le nœud cloné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlElement](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)