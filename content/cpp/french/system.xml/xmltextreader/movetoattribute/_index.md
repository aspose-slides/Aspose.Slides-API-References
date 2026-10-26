---
title: MoveToAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Déplace le lecteur vers l'attribut portant le nom spécifié.
type: docs
weight: 508
url: /fr/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) méthode

Déplace le lecteur vers l'attribut portant le nom spécifié.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'attribut. |

### Valeur de retour

**true** si l'attribut est trouvé ; sinon, **false**. Si **false**, la position du lecteur ne change pas.

## XmlTextReader::MoveToAttribute(String, String) méthode

Déplace le lecteur vers l'attribut portant le nom local et l'URI d'espace de noms spécifiés.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut. |

### Valeur de retour

**true** si l'attribut est trouvé ; sinon, **false**. Si **false**, la position du lecteur ne change pas.

## XmlTextReader::MoveToAttribute(int32_t) méthode

Déplace le lecteur vers l'attribut portant l'indice spécifié.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| i | **int32_t** | L'indice de l'attribut. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)