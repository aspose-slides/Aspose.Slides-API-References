---
title: XmlValidatingReader()
second_title: Aspose.Slides pro C++ – reference API
description: Inicializuje novou instanci třídy XmlValidatingReader, která ověřuje obsah vrácený z daného XmlReader.
type: docs
weight: 430
url: /cs/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor

Inicializuje novou instanci třídy [XmlValidatingReader](../), která ověřuje obsah vrácený z daného [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | [XmlReader](../../xmlreader/) pro čtení během ověřování. Aktuální implementace podporuje pouze [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Inicializuje novou instanci třídy [XmlValidatingReader](../) s uvedenými hodnotami.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Řetězec obsahující XML fragment k analýze. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType XML fragmentu. Tím se také určuje, co může řetězec fragmentu obsahovat (viz tabulka níže). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/), ve kterém má být XML fragment analyzován. To zahrnuje [NameTable](../../nametable/) k použití, kódování, rozsah jmenného prostoru, aktuální **xml:lang** a **xml:space**. |

## Poznámky

Následující tabulka uvádí platné hodnoty pro **fragType** a způsob, jakým čteč zpracovává jednotlivé typy uzlů.

| XmlNodeType | Fragment může obsahovat |
| --- | --- |
| Element| Jakýkoli platný obsah elementu (například libovolná kombinace elementů, komentářů, instrukcí zpracování, cdata, textu a odkazů na entity). |
| [Attribute](../../../system/attribute/)| Hodnota atributu (část uvnitř uvozovek). |
| Document| Obsah celého XML dokumentu; toto vynucuje pravidla na úrovni dokumentu. |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Inicializuje novou instanci třídy [XmlValidatingReader](../) s uvedenými hodnotami.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud obsahující XML fragment k analýze. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType XML fragmentu. Určuje, co může fragment obsahovat (viz tabulka níže). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/), ve kterém má být XML fragment analyzován. To zahrnuje [XmlNameTable](../../xmlnametable/) k použití, kódování, rozsah jmenného prostoru, aktuální **xml:lang** a **xml:space**. |

## Poznámky

Následující tabulka uvádí platné hodnoty pro **fragType** a způsob, jakým čteč zpracovává jednotlivé typy uzlů.

| XmlNodeType | Fragment může obsahovat |
| --- | --- |
| Element| Jakýkoli platný obsah elementu (například libovolná kombinace elementů, komentářů, instrukcí zpracování, cdata, textu a odkazů na entity). |
| [Attribute](../../../system/attribute/)| Hodnota atributu (část uvnitř uvozovek). |
| Document| Obsah celého XML dokumentu; toto vynucuje pravidla na úrovni dokumentu. |

## Viz také

* Výčet [XmlNodeType](../../xmlnodetype/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [XmlReader](../../xmlreader/)
* Třída [XmlValidatingReader](../)
* Třída [String](../../../system/string/)
* Třída [XmlParserContext](../../xmlparsercontext/)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)