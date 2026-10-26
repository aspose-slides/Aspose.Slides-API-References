---
title: SelectNodes()
second_title: Référence de l'API Aspose.Slides for C++
description: Sélectionne une liste de nœuds correspondant à l'expression XPath.
type: docs
weight: 365
url: /fr/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) méthode

Sélectionne une liste de nœuds correspondant à l'expression [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | L'expression [XPath](../../../system.xml.xpath/). |

### Valeur de retour

Un [XmlNodeList](../../xmlnodelist/) contenant une collection de nœuds correspondant à la requête [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) méthode

Sélectionne une liste de nœuds correspondant à l'expression [XPath](../../../system.xml.xpath/). Tous les préfixes trouvés dans l'expression [XPath](../../../system.xml.xpath/) sont résolus à l'aide du [XmlNamespaceManager](../../xmlnamespacemanager/) fourni.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | L'expression [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Un [XmlNamespaceManager](../../xmlnamespacemanager/) à utiliser pour résoudre les espaces de noms des préfixes dans l'expression [XPath](../../../system.xml.xpath/). |

### Valeur de retour

Un [XmlNodeList](../../xmlnodelist/) contenant une collection de nœuds correspondant à la requête [XPath](../../../system.xml.xpath/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNodeList](../../xmlnodelist/)
* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Classe [XmlNamespaceManager](../../xmlnamespacemanager/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)