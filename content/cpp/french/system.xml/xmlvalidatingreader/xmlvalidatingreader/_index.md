---
title: XmlValidatingReader()
second_title: Référence API Aspose.Slides pour C++
description: Initialise une nouvelle instance de la classe XmlValidatingReader qui valide le contenu renvoyé par le XmlReader donné.
type: docs
weight: 430
url: /fr/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructeur

Initialise une nouvelle instance de la classe [XmlValidatingReader](../) qui valide le contenu renvoyé par le [XmlReader](../../xmlreader/) fourni.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | Le [XmlReader](../../xmlreader/) à lire pendant la validation. L'implémentation actuelle ne prend en charge que [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructeur

Initialise une nouvelle instance de la classe [XmlValidatingReader](../) avec les valeurs spécifiées.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | La chaîne contenant le fragment XML à analyser. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Le XmlNodeType du fragment XML. Cela détermine également ce que la chaîne du fragment peut contenir (voir le tableau ci-dessus). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Le [XmlParserContext](../../xmlparsercontext/) dans lequel le fragment XML doit être analysé. Cela inclut le [NameTable](../../nametable/) à utiliser, l'encodage, la portée du namespace, la portée actuelle de **xml:lang** et de **xml:space**. |

## Remarques

Le tableau suivant répertorie les valeurs valides pour **fragType** et la façon dont le lecteur analyse chacun des différents types de nœuds.

| XmlNodeType | Fragment peut contenir |
| --- | --- |
| Element| Tout contenu d'élément valide (par exemple, toute combinaison d'éléments, de commentaires, d'instructions de traitement, de CDATA, de texte et de références d'entité). |
| [Attribute](../../../system/attribute/)| La valeur d'un attribut (la partie entre les guillemets). |
| Document| Le contenu d'un document XML complet ; cela impose les règles au niveau du document. |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructeur

Initialise une nouvelle instance de la classe [XmlValidatingReader](../) avec les valeurs spécifiées.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux contenant le fragment XML à analyser. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Le XmlNodeType du fragment XML. Cela détermine ce que le fragment peut contenir (voir le tableau ci-dessus). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Le [XmlParserContext](../../xmlparsercontext/) dans lequel le fragment XML doit être analysé. Cela inclut le [XmlNameTable](../../xmlnametable/) à utiliser, l'encodage, la portée du namespace, la portée actuelle de **xml:lang** et de **xml:space**. |

## Remarques

Le tableau suivant répertorie les valeurs valides pour **fragType** et la façon dont le lecteur analyse chacun des différents types de nœuds.

| XmlNodeType | Fragment peut contenir |
| --- | --- |
| Element| Tout contenu d'élément valide (par exemple, toute combinaison d'éléments, de commentaires, d'instructions de traitement, de CDATA, de texte et de références d'entité). |
| [Attribute](../../../system/attribute/)| La valeur d'un attribut (la partie entre les guillemets). |
| Document| Le contenu d'un document XML complet ; cela impose les règles au niveau du document. |

## Voir aussi

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../xmlreader/)
* Classe [XmlValidatingReader](../)
* Classe [String](../../../system/string/)
* Classe [XmlParserContext](../../xmlparsercontext/)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)