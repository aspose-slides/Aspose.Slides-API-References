---
title: XmlValidatingReader()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av XmlValidatingReader-klassen som validerar innehållet som returneras från den angivna XmlReader.
type: docs
weight: 430
url: /sv/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor

Initierar en ny instans av [XmlValidatingReader](../) klass som validerar innehållet som returneras från den angivna [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | Den [XmlReader](../../xmlreader/) att läsa från medan validering. Den aktuella implementeringen stöder endast [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Initierar en ny instans av [XmlValidatingReader](../) klass med de angivna värdena.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Strängen som innehåller XML-fragmentet att parsa. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType för XML-fragmentet. Detta bestämmer också vad fragmentsträngen kan innehålla (se tabellen nedan). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Den [XmlParserContext](../../xmlparsercontext/) i vilken XML-fragmentet skall parsas. Detta inkluderar [NameTable](../../nametable/) att använda, kodning, namnrymdsområde, aktuell **xml:lang** och **xml:space**-omfång. |

## Anmärkningar

Följande tabell listar giltiga värden för **fragType** och hur läsaren tolkar varje av de olika nodtyperna.

| XmlNodeType | Fragment kan innehålla |
| --- | --- |
| Element | Alla giltiga elementinnehåll (till exempel en kombination av element, kommentarer, processinstruktioner, cdata, text och entitetsreferenser). |
| [Attribute](../../../system/attribute/) | Värdet av ett attribut (delen innanför citattecknen). |
| Document | Innehållet i ett helt XML-dokument; detta verkställer dokumentnivåregler. |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Initierar en ny instans av [XmlValidatingReader](../) klass med de angivna värdena.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som innehåller XML-fragmentet att parsa. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType för XML-fragmentet. Detta bestämmer vad fragmentet kan innehålla (se tabellen nedan). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Den [XmlParserContext](../../xmlparsercontext/) i vilken XML-fragmentet ska parsas. Detta inkluderar [XmlNameTable](../../xmlnametable/) att använda, kodning, namnrymdsområde, aktuell **xml:lang** och **xml:space**-omfång. |

## Anmärkningar

Följande tabell listar giltiga värden för **fragType** och hur läsaren tolkar varje av de olika nodtyperna.

| XmlNodeType | Fragment kan innehålla |
| --- | --- |
| Element | Alla giltiga elementinnehåll (till exempel en kombination av element, kommentarer, processinstruktioner, cdata, text och entitetsreferenser). |
| [Attribute](../../../system/attribute/) | Värdet av ett attribut (delen innanför citattecknen). |
| Document | Innehållet i ett helt XML-dokument; detta verkställer dokumentnivåregler. |

## Se också

* Enum [XmlNodeType](../../xmlnodetype/)
* Typdef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlReader](../../xmlreader/)
* Klass [XmlValidatingReader](../)
* Klass [String](../../../system/string/)
* Klass [XmlParserContext](../../xmlparsercontext/)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)