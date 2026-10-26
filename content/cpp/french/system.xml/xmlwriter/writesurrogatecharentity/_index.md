---
title: WriteSurrogateCharEntity()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est redéfinie dans une classe dérivée, génère et écrit l'entité de caractères de substitution pour la paire de caractères de substitution.
type: docs
weight: 261
url: /fr/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) méthode

Lorsqu'elle est redéfinie dans une classe dérivée, génère et écrit l'entité de caractère de remplacement pour la paire de caractères de remplacement.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lowChar | char16_t | Le caractère de remplacement bas. Il doit être une valeur comprise entre 0xDC00 et 0xDFFF. |
| highChar | char16_t | Le caractère de remplacement haut. Il doit être une valeur comprise entre 0xD800 et 0xDBFF. |

## Voir aussi

* Classe [XmlWriter](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)