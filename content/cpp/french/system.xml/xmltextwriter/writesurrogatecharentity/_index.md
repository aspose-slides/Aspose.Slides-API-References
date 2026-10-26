---
title: WriteSurrogateCharEntity()
second_title: Référence API Aspose.Slides pour C++
description: Génère et écrit l’entité de caractère de substitution pour la paire de caractères de substitution.
type: docs
weight: 391
url: /fr/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) méthode


Génère et écrit l’entité de caractère de substitution pour la paire de caractères de substitution.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lowChar | char16_t | Le caractère de substitution faible. Il doit être une valeur comprise entre **0xDC00** et **0xDFFF**. |
| highChar | char16_t | Le caractère de substitution élevé. Il doit être une valeur comprise entre **0xD800** et **0xDBFF**. |

## Voir aussi

* Classe [XmlTextWriter](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)