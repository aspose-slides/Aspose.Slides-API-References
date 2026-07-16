---
title: MoveToAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Lorsqu'elle est remplacée dans une classe dérivée, se déplace vers l'attribut dont la valeur XmlReader::get_Name est spécifiée."
type: docs
weight: 625
url: /fr/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) méthode

Lorsqu'elle est remplacée dans une classe dérivée, se déplace vers l'attribut dont la valeur [XmlReader::get_Name](../get_name/) est spécifiée.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom complet de l'attribut. |

### Valeur de retour

**true** si l'attribut est trouvé ; sinon, **false**. Si **false**, la position du lecteur ne change pas.

## XmlReader::MoveToAttribute(String, String) méthode

Lorsqu'elle est remplacée dans une classe dérivée, se déplace vers l'attribut dont les valeurs [XmlReader::get_LocalName](../get_localname/) et [XmlReader::get_NamespaceURI](../get_namespaceuri/) sont spécifiées.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom local de l'attribut. |
| ns | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut. |

### Valeur de retour

**true** si l'attribut est trouvé ; sinon, **false**. Si **false**, la position du lecteur ne change pas.

## XmlReader::MoveToAttribute(int32_t) méthode

Lorsqu'elle est remplacée dans une classe dérivée, se déplace vers l'attribut dont l'index est spécifié.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | **int32_t** | L'index de l'attribut. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)