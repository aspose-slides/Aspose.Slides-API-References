---
title: MoveToAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Déplace le lecteur vers l'attribut dont le nom est spécifié.
type: docs
weight: 456
url: /fr/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) méthode

Déplace le lecteur vers l'attribut dont le nom est spécifié.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'attribut. |

### Valeur de retour

**true** si l'attribut est trouvé ; sinon, **false**. Si **false**, la position du lecteur ne change pas.

## XmlValidatingReader::MoveToAttribute(String, String) méthode

Déplace le lecteur vers l'attribut dont le nom local et l'URI d'espace de noms sont spécifiés.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut. |

### Valeur de retour

**true** si l'attribut est trouvé ; sinon, **false**. Si **false**, la position du lecteur ne change pas.

## XmlValidatingReader::MoveToAttribute(int32_t) méthode

Déplace le lecteur vers l'attribut dont l'index est spécifié.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | **int32_t** | L'index de l'attribut. |

## Voir également

* Classe [String](../../../system/string/)
* Classe [XmlValidatingReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)