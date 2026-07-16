---
title: ReadString()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit le contenu d'un élément ou d'un nœud texte sous forme de chaîne.
type: docs
weight: 391
url: /fr/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() méthode

Lit le contenu d'un élément ou d'un nœud texte sous forme de chaîne.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```

### Valeur de retour

Le contenu de l'élément ou du nœud de type texte (cela peut inclure les nœuds CDATA, [Text](../../../system.text/) et ainsi de suite). Cela peut être une chaîne vide si le lecteur est positionné sur autre chose qu'un élément ou un nœud texte, ou s'il n'y a plus de contenu texte à retourner dans le contexte actuel. Remarque : le nœud texte peut être soit un élément, soit un nœud texte d'attribut.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)