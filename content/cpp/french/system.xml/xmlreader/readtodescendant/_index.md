---
title: ReadToDescendant()
second_title: Référence de l'API Aspose.Slides pour C++
description: Avance le XmlReader vers l'élément descendant suivant avec le nom qualifié spécifié.
type: docs
weight: 911
url: /fr/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) méthode

Avance le [XmlReader](../) vers l'élément descendant suivant avec le nom qualifié spécifié.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'élément vers lequel vous souhaitez vous déplacer. |

### Valeur de retour

**true** si un élément descendant correspondant est trouvé ; sinon **false**. Si aucun élément enfant correspondant n'est trouvé, le [XmlReader](../) est positionné sur la balise de fin (la valeur [XmlReader::get_NodeType](../get_nodetype/) est [XmlNodeType::EndElement](../../xmlnodetype/)) de l'élément. Si le [XmlReader](../) n'est pas positionné sur un élément lorsque [XmlReader::ReadToDescendant(String)](./) a été appelé, cette méthode renvoie **false** et la position du [XmlReader](../) n'est pas modifiée.

## XmlReader::ReadToDescendant(String, String) méthode

Avance le [XmlReader](../) vers l'élément descendant suivant avec le nom local et l'URI d'espace de noms spécifiés.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'élément vers lequel vous souhaitez vous déplacer. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'élément vers lequel vous souhaitez vous déplacer. |

### Valeur de retour

**true** si un élément descendant correspondant est trouvé ; sinon **false**. Si aucun élément enfant correspondant n'est trouvé, le [XmlReader](../) est positionné sur la balise de fin (la valeur [XmlReader::get_NodeType](../get_nodetype/) est [XmlNodeType::EndElement](../../xmlnodetype/)) de l'élément. Si le [XmlReader](../) n'est pas positionné sur un élément lorsque [XmlReader::ReadToDescendant(String,String)](./) a été appelé, cette méthode renvoie **false** et la position du [XmlReader](../) n'est pas modifiée.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)