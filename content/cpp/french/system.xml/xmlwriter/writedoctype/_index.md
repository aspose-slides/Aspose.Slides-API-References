---
title: WriteDocType()
second_title: Référence API Aspose.Slides pour C++
description: Lorsqu'elle est redéfinie dans une classe dérivée, écrit la déclaration DOCTYPE avec le nom spécifié et les attributs optionnels.
type: docs
weight: 79
url: /fr/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) méthode


When overridden in a derived class, writes the DOCTYPE declaration with the specified name and optional attributes.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Le nom du DOCTYPE. Il doit être non vide. |
| pubid | const [String](../../../system/string/)\& | Si non nul, il écrit également PUBLIC \"pubid\" \"sysid\" où **pubid** et **sysid** sont remplacés par la valeur des arguments fournis. |
| sysid | const [String](../../../system/string/)\& | Si **pubid** est **nullptr** et que **sysid** est non nul, il écrit SYSTEM \"sysid\" où **sysid** est remplacé par la valeur de cet argument. |
| subset | const [String](../../../system/string/)\& | Si non nul, il écrit [subset] où subset est remplacé par la valeur de cet argument. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)