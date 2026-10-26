---
title: MoveToContent()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Vérifie si le nœud actuel est un nœud de contenu (texte non blanc, CDATA, Element, EndElement, EntityReference ou EndEntity). Si le nœud n'est pas un nœud de contenu, le lecteur avance jusqu'au prochain nœud de contenu ou à la fin du fichier. Il ignore les nœuds du type suivant : ProcessingInstruction, DocumentType, Comment, Whitespace ou SignificantWhitespace."
type: docs
weight: 833
url: /fr/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() method


Vérifie si le nœud actuel est un nœud de contenu (texte non blanc, **CDATA**, **Element**, **EndElement**, **EntityReference**, ou **EndEntity**). Si le nœud n’est pas un nœud de contenu, le lecteur avance jusqu’au prochain nœud de contenu ou à la fin du fichier. Il ignore les nœuds du type suivant : **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, ou **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### Valeur de retour

The [XmlReader::get_NodeType](../get_nodetype/) value of the current node found by the method or [XmlNodeType::None](../../xmlnodetype/) if the reader has reached the end of the input stream.

## Voir aussi

* Enum [XmlNodeType](../../xmlnodetype/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)