---
title: ReadElementContentAsObject()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit l'élément actuel et renvoie le contenu sous forme d'un Object.
type: docs
weight: 469
url: /fr/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() méthode

Lit l'élément actuel et renvoie le contenu sous forme d'un [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Valeur de retour

Un objet encapsulé du type le plus approprié. La valeur [XmlReader::get_ValueType](../get_valuetype/) détermine le type approprié. Si le contenu est typé comme un type de liste, cette méthode renvoie un tableau d'objets encapsulés du type approprié.

## XmlReader::ReadElementContentAsObject(String, String) méthode

Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit l'élément actuel et renvoie le contenu sous forme d'un [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'élément. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'élément. |

### Valeur de retour

Un objet encapsulé du type le plus approprié. La valeur [XmlReader::get_ValueType](../get_valuetype/) détermine le type approprié. Si le contenu est typé comme un type de liste, cette méthode renvoie un tableau d'objets encapsulés du type approprié.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)