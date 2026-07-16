---
title: ReadStartElement()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie que le nœud actuel est un élément et avance le lecteur au nœud suivant.
type: docs
weight: 846
url: /fr/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() méthode

Vérifie que le nœud actuel est un élément et avance le lecteur au nœud suivant.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) méthode

Vérifie que le nœud de contenu actuel est un élément avec la valeur [XmlReader::get_Name](../get_name/) donnée et avance le lecteur au nœud suivant.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'élément. |

## XmlReader::ReadStartElement(String, String) méthode

Vérifie que le nœud de contenu actuel est un élément avec les valeurs [XmlReader::get_LocalName](../get_localname/) et [XmlReader::get_NamespaceURI](../get_namespaceuri/) données et avance le lecteur au nœud suivant.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Le nom local de l'élément. |
| ns | [String](../../../system/string/) | L'URI de l'espace de noms de l'élément. |

## Voir aussi

* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)