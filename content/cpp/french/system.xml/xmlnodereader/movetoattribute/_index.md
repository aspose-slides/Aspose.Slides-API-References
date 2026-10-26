---
title: MoveToAttribute()
second_title: Référence API Aspose.Slides pour C++
description: Déplace le lecteur vers l'attribut dont le nom est spécifié.
type: docs
weight: 300
url: /fr/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) méthode

Déplace le lecteur vers l'attribut dont le nom est spécifié.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'attribut. |

### Valeur de retour

**true** si l'attribut est trouvé ; sinon, **false**. Si **false**, la position du lecteur ne change pas.

## XmlNodeReader::MoveToAttribute(String, String) méthode

Déplace le lecteur vers l'attribut dont le nom local et l'URI de l'espace de noms sont spécifiés.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI de l'espace de noms de l'attribut. |

### Valeur de retour

**true** si l'attribut est trouvé ; sinon, **false**. Si **false**, la position du lecteur ne change pas.

## XmlNodeReader::MoveToAttribute(int32_t) méthode

Déplace le lecteur vers l'attribut dont l'index est spécifié.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| attributeIndex | **int32_t** | L'index de l'attribut. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)