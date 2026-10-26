---
title: get_LocalName()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, obtient le nom local du nœud actuel.
type: docs
weight: 40
url: /fr/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() méthode


Lorsqu'elle est remplacée dans une classe dérivée, obtient le nom local du nœud actuel.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### Valeur de retour

Le nom du nœud actuel sans le préfixe. Par exemple, **LocalName** est **book** pour l'élément **<bk:book>**. Pour les types de nœuds qui n'ont pas de nom (comme **[Text](../../../system.text/)**, **Comment**, etc.), cette méthode renvoie [String::Empty](../../../system/string/empty/).

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)