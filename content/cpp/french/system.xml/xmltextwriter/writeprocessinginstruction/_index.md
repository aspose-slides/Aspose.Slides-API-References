---
title: WriteProcessingInstruction()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Écrit une instruction de traitement avec un espace entre le nom et le texte comme suit : <?name text?>."
type: docs
weight: 326
url: /fr/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) méthode

Écrit une instruction de traitement avec un espace entre le nom et le texte comme suit : **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nom de l'instruction de traitement. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) à inclure dans l'instruction de traitement. |
## Remarques

Cette méthode est utilisée pour créer une déclaration XML après que [XmlTextWriter::WriteStartDocument](../writestartdocument/) a déjà été appelée.
## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlTextWriter](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)