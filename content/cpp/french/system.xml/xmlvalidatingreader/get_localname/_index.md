---
title: get_LocalName()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le nom local du nœud actuel.
type: docs
weight: 27
url: /fr/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() method

Retourne le nom local du nœud actuel.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```

### Valeur de retour

Le nom du nœud actuel sans le préfixe. Par exemple, **LocalName** est **book** pour l'élément **<bk:book>**. Pour les types de nœuds qui n'ont pas de nom (comme **[Text](../../../system.text/)**, **Comment**, etc.), cette méthode renvoie [String::Empty](../../../system/string/empty/).

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlValidatingReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)