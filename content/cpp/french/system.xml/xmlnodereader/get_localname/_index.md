---
title: get_LocalName()
second_title: Référence de l'API Aspose.Slides for C++ 
description: Renvoie le nom local du nœud actuel.
type: docs
weight: 27
url: /fr/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() méthode

Renvoie le nom local du nœud actuel.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```

### Valeur de retour

Le nom du nœud actuel avec le préfixe supprimé. Par exemple, **LocalName** est **book** pour l'élément **<bk:book>**. Pour les types de nœuds qui n'ont pas de nom (comme **[Text](../../../system.text/)**, **Comment**, etc.), cette méthode renvoie [String::Empty](../../../system/string/empty/).

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)