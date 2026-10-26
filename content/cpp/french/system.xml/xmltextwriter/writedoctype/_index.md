---
title: WriteDocType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit la déclaration DOCTYPE avec le nom spécifié et les attributs optionnels.
type: docs
weight: 222
url: /fr/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) method

Écrit la déclaration DOCTYPE avec le nom spécifié et les attributs optionnels.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Le nom du DOCTYPE. Il doit être non vide. |
| pubid | const [String](../../../system/string/)\& | S’il n’est pas nul, écrit également PUBLIC "pubid" "sysid" où **pubid** et **sysid** sont remplacés par la valeur des arguments fournis. |
| sysid | const [String](../../../system/string/)\& | Si **pubid** est nul et **sysid** n’est pas nul, écrit SYSTEM "sysid" où **sysid** est remplacé par la valeur de cet argument. |
| subset | const [String](../../../system/string/)\& | S’il n’est pas nul, écrit [subset] où subset est remplacé par la valeur de cet argument. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlTextWriter](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)