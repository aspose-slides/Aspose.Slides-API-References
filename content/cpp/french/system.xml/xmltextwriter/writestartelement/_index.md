---
title: WriteStartElement()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit la balise de départ spécifiée et l'associe à l'espace de noms et au préfixe fournis.
type: docs
weight: 235
url: /fr/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) méthode

Écrit la balise de départ spécifiée et l'associe à l'espace de noms et au préfixe fournis.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Le préfixe d'espace de noms de l'élément. |
| localName | const [String](../../../system/string/)\& | Le nom local de l'élément. |
| ns | const [String](../../../system/string/)\& | L'URI de l'espace de noms à associer à l'élément. Si cet espace de noms est déjà en portée et possède un préfixe associé, l'écrivain écrit automatiquement ce préfixe également. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlTextWriter](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)