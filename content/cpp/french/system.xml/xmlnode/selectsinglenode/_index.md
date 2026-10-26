---
title: SelectSingleNode()
second_title: Référence API Aspose.Slides pour C++
description: Sélectionne le premier XmlNode qui correspond à l'expression XPath.
type: docs
weight: 352
url: /fr/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) method

Sélectionne le premier [XmlNode](../) qui correspond à l'expression [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | L'expression [XPath](../../../system.xml.xpath/). |

### Valeur de retour

Le premier [XmlNode](../) qui correspond à la requête [XPath](../../../system.xml.xpath/) ou **nullptr** si aucun nœud correspondant n'est trouvé.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method

Sélectionne le premier [XmlNode](../) qui correspond à l'expression [XPath](../../../system.xml.xpath/). Tous les préfixes trouvés dans l'expression [XPath](../../../system.xml.xpath/) sont résolus à l'aide du [XmlNamespaceManager](../../xmlnamespacemanager/) fourni.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | L'expression [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Un [XmlNamespaceManager](../../xmlnamespacemanager/) à utiliser pour résoudre les espaces de noms des préfixes dans l'expression [XPath](../../../system.xml.xpath/). |

### Valeur de retour

Le premier [XmlNode](../) qui correspond à la requête [XPath](../../../system.xml.xpath/) ou **nullptr** si aucun nœud correspondant n'est trouvé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)