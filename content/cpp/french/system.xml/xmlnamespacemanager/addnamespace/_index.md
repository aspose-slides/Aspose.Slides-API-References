---
title: AddNamespace()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute l'espace de noms fourni à la collection.
type: docs
weight: 66
url: /fr/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) méthode

Ajoute l'espace de noms fourni à la collection.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Le préfixe à associer à l'espace de noms ajouté. Utilisez [String::Empty](../../../system/string/empty/) pour ajouter un espace de noms par défaut. Si le [XmlNamespaceManager](../) sera utilisé pour résoudre les espaces de noms dans une expression XML Path Language ([XPath](../../../system.xml.xpath/)), un préfixe doit être spécifié. Si une expression [XPath](../../../system.xml.xpath/) n'inclut pas de préfixe, il est supposé que l'identifiant uniforme de ressource (URI) de l'espace de noms est l'espace de noms vide. Pour plus d'informations sur les expressions [XPath](../../../system.xml.xpath/) et le [XmlNamespaceManager](../), reportez-vous aux méthodes XmlNode::SelectNodes(String) et XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) |
| uri | [String](../../../system/string/) | L'espace de noms à ajouter. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)