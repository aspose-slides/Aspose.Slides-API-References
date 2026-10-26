---
title: XmlValidatingReader()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy új példányt az XmlValidatingReader osztályból, amely érvényesíti a megadott XmlReader által visszaadott tartalmat.
type: docs
weight: 430
url: /hu/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) konstruktor


Létrehoz egy új példányt a [XmlValidatingReader](../) osztályból, amely érvényesíti a megadott [XmlReader](../../xmlreader/) által visszaadott tartalmat.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | A [XmlReader](../../xmlreader/) amelyből a validálás során olvas. A jelenlegi megvalósítás csak a [XmlTextReader](../../xmltextreader/)-t támogatja. |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) konstruktor


Létrehoz egy új példányt a [XmlValidatingReader](../) osztályból a megadott értékekkel.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Az XML töredéket tartalmazó karakterlánc. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Az XML töredék XmlNodeType-ja. Ez határozza meg, hogy a töredék karakterlánc mit tartalmazhat (lásd alább a táblázatot). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | A [XmlParserContext](../../xmlparsercontext/) amelyben az XML töredéket elemezni kell. Ez tartalmazza a használandó [NameTable](../../nametable/), kódolást, névtér hatókört, a jelenlegi **xml:lang**, és **xml:space** hatókört. |
## Megjegyzések



Az alábbi táblázat felsorolja a **fragType** érvényes értékeit és azt, hogy az olvasó hogyan dolgozza fel az egyes csomóponttípusokat. 

| XmlNodeType | A töredék tartalmazhat |
| --- | --- |
| Element| Bármilyen érvényes elem tartalom (például bármilyen kombinációja az elemeknek, megjegyzéseknek, feldolgozási utasításoknak, cdata-nak, szövegnek és entitás hivatkozásoknak). |
| [Attribute](../../../system/attribute/)| Az attribútum értéke (a idézőjelek közötti rész). |
| Document| Az egész XML dokumentum tartalma; ez dokumentumszintű szabályokat kényszerít. |


## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) konstruktor


Létrehoz egy új példányt a [XmlValidatingReader](../) osztályból a megadott értékekkel.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az XML töredéket tartalmazó adatfolyam. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Az XML töredék XmlNodeType-ja. Ez határozza meg, hogy a töredék mit tartalmazhat (lásd alább a táblázatot). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | A [XmlParserContext](../../xmlparsercontext/) amelyben az XML töredéket elemezni kell. Ez tartalmazza a használandó [XmlNameTable](../../xmlnametable/), kódolást, névtér hatókört, a jelenlegi **xml:lang**, és **xml:space** hatókört. |
## Megjegyzések



Az alábbi táblázat felsorolja a **fragType** érvényes értékeit és azt, hogy az olvasó hogyan dolgozza fel az egyes csomóponttípusokat. 

| XmlNodeType | A töredék tartalmazhat |
| --- | --- |
| Element| Bármilyen érvényes elem tartalom (például bármilyen kombinációja az elemeknek, megjegyzéseknek, feldolgozási utasításoknak, cdata-nak, szövegnek és entitás hivatkozásoknak). |
| [Attribute](../../../system/attribute/)| Az attribútum értéke (a idézőjelek közötti rész). |
| Document| Az egész XML dokumentum tartalma; ez dokumentumszintű szabályokat kényszerít. |


## Lásd még

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)