---
title: WriteProcessingInstruction()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Lorsqu'elle est redéfinie dans une classe dérivée, écrit une instruction de traitement avec un espace entre le nom et le texte comme suit : <?name text?>."
type: docs
weight: 196
url: /fr/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) méthode

Lorsqu'elle est redéfinie dans une classe dérivée, écrit une instruction de traitement avec un espace entre le nom et le texte comme suit : **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom de l'instruction de traitement. |
| text | [String](../../../system/string/) | Le texte à inclure dans l'instruction de traitement. |
## Remarques

Cette méthode est utilisée pour créer une déclaration XML après que [XmlWriter::WriteStartDocument](../writestartdocument/) a déjà été appelée. 
## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)