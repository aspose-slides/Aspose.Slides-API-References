---
title: ReadToNextSibling()
second_title: Référence de l'API Aspose.Slides pour C++
description: Avance le XmlReader vers l'élément frère suivant avec le nom qualifié spécifié.
type: docs
weight: 924
url: /fr/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) méthode

Avance le [XmlReader](../) vers l'élément frère suivant avec le nom qualifié spécifié.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'élément frère vers lequel vous souhaitez vous déplacer. |

### Valeur de retour

**true** si un élément frère correspondant est trouvé ; sinon **false**. Si aucun élément frère correspondant n'est trouvé, le [XmlReader](../) est positionné sur la balise de fin (valeur [XmlReader::get_NodeType](../get_nodetype/) est [XmlNodeType::EndElement](../../xmlnodetype/)) de l'élément parent.

## XmlReader::ReadToNextSibling(String, String) méthode

Avance le [XmlReader](../) vers l'élément frère suivant avec le nom local et l'URI d'espace de noms spécifiés.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'élément frère vers lequel vous souhaitez vous déplacer. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'élément frère vers lequel vous souhaitez vous déplacer. |

### Valeur de retour

**true** si un élément frère correspondant est trouvé ; sinon **false**. Si aucun élément frère correspondant n'est trouvé, le [XmlReader](../) est positionné sur la balise de fin (valeur [XmlReader::get_NodeType](../get_nodetype/) est [XmlNodeType::EndElement](../../xmlnodetype/)) de l'élément parent.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)