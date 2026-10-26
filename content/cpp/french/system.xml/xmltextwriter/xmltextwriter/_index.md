---
title: XmlTextWriter()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Crée une instance de la classe XmlTextWriter en utilisant le flux et l'encodage spécifiés."
type: docs
weight: 183
url: /fr/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructeur

Crée une instance de la classe [XmlTextWriter](../) en utilisant le flux et l'encodage spécifiés.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux vers lequel vous souhaitez écrire. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | L'encodage à générer. Si l'encodage est **nullptr**, il écrit le flux en UTF-8 et omet l'attribut d'encodage du **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructeur

Crée une instance de la classe [XmlTextWriter](../) en utilisant le fichier spécifié.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Le nom de fichier dans lequel écrire. Si le fichier existe, il le tronque et le remplace par le nouveau contenu. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | L'encodage à générer. Si l'encodage est **nullptr**, il écrit le fichier en UTF-8 et omet l'attribut d'encodage du **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructeur

Crée une instance de la classe [XmlTextWriter](../) en utilisant le TextWriter spécifié.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Le TextWriter dans lequel écrire. On suppose que le TextWriter est déjà configuré avec le bon encodage. |

## Voir également

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [Encoding](../../../system.text/encoding/)
* Classe [XmlTextWriter](../)
* Classe [String](../../../system/string/)
* Classe [TextWriter](../../../system.io/textwriter/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)