---
title: CreateXmlDeclaration()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nœud XmlDeclaration avec les valeurs spécifiées.
type: docs
weight: 378
url: /fr/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) méthode

Crée un nœud [XmlDeclaration](../../xmldeclaration/) avec les valeurs spécifiées.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | La version doit être \"1.0\". |
| encoding | const [String](../../../system/string/)\& | La valeur de l'attribut d'encodage. C'est l'encodage qui est utilisé lorsque vous enregistrez le [XmlDocument](../) dans un fichier ou un flux ; par conséquent, il doit être défini sur une chaîne prise en charge par la classe [Text::Encoding](../../../system.text/encoding/), sinon \"XmlDocument::Save(String)\" échoue. Si c'est **nullptr** ou [String::Empty](../../../system/string/empty/), la méthode [XmlDocument::Save](../save/) n'écrit pas d'attribut d'encodage dans la déclaration XML et, par conséquent, l'encodage par défaut, UTF-8, est utilisé. |
| standalone | const [String](../../../system/string/)\& | La valeur doit être soit \"yes\" soit \"no\". Si c'est **nullptr** ou [String::Empty](../../../system/string/empty/), la méthode [XmlDocument::Save](../save/) n'écrit pas d'attribut standalone dans la déclaration XML. |

### Valeur de retour

Le nouveau nœud [XmlDeclaration](../../xmldeclaration/).

## Remarques

Remarque : Si le [XmlDocument](../) est enregistré dans un TextWriter ou un [XmlTextWriter](../../xmltextwriter/), cette valeur d'encodage est ignorée. À la place, l'encodage du TextWriter ou du [XmlTextWriter](../../xmltextwriter/) est utilisé. Cela garantit que le XML écrit peut être relu en utilisant l'encodage correct.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlDeclaration](../../xmldeclaration/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)