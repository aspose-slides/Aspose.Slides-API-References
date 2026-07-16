---
title: ReadToFollowing()
second_title: Référence API Aspose.Slides pour C++
description: Lit jusqu'à ce qu'un élément portant le nom qualifié spécifié soit trouvé.
type: docs
weight: 898
url: /fr/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) méthode

Lit jusqu'à ce qu'un élément portant le nom qualifié spécifié soit trouvé.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'élément. |

### Valeur de retour

**true** si un élément correspondant est trouvé ; sinon **false** et le [XmlReader](../) est dans un état de fin de fichier.

## XmlReader::ReadToFollowing(String, String) méthode

Lit jusqu'à ce qu'un élément portant le nom local et l'URI d'espace de noms spécifiés soit trouvé.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'élément. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'élément. |

### Valeur de retour

**true** si un élément correspondant est trouvé ; sinon **false** et le [XmlReader](../) est dans un état de fin de fichier.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)