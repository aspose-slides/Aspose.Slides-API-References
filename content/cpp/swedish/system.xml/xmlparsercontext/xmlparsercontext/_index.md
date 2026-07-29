---
title: XmlParserContext()
second_title: Aspose.Slides för C++ API-referens
description: "Initierar en ny instans av klassen XmlParserContext med de angivna XmlNameTable, XmlNamespaceManager, xml:lang och xml:space värdena."
type: docs
weight: 261
url: /sv/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) konstruktor

Initierar en ny instans av klassen [XmlParserContext](../) med de angivna [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** och **xml:space** värdena.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) att använda för att atomisera strängar. Om detta är **nullptr** används namntabellen som användes för att konstruera **nsMgr** i stället. För mer information om atomiserade strängar, se [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) att använda för att slå upp namnrymdsinformation, eller **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang**-omfånget. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Ett XmlSpace-värde som anger **xml:space**-omfånget. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) konstruktor

Initierar en ny instans av klassen [XmlParserContext](../) med de angivna [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** och kodning.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) att använda för att atomisera strängar. Om detta är **nullptr** används namntabellen som användes för att konstruera **nsMgr** i stället. För mer information om atomiserade strängar, se [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) att använda för att slå upp namnrymdsinformation, eller **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang**-omfånget. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Ett XmlSpace-värde som anger **xml:space**-omfånget. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Ett Encoding-objekt som anger kodningsinställningen. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) konstruktor

Initierar en ny instans av klassen [XmlParserContext](../) med de angivna [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), bas-URI, **xml:lang**, **xml:space** och dokumenttypvärdena.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) att använda för att atomisera strängar. Om detta är **nullptr** används namntabellen som användes för att konstruera **nsMgr** i stället. För mer information om atomiserade strängar, se [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) att använda för att slå upp namnrymdsinformation, eller **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Namnet på dokumenttypdeklarationen. |
| pubId | const [String](../../../system/string/)\& | Den offentliga identifieraren. |
| sysId | const [String](../../../system/string/)\& | Systemidentifieraren. |
| internalSubset | const [String](../../../system/string/)\& | Det interna DTD-delmängden. DTD-delmängden används för entitetsupplösning, inte för dokumentvalidering. |
| baseURI | const [String](../../../system/string/)\& | Bas-URI för XML-fragmentet (platsen fragmentet laddades från). |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang**-omfånget. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Ett XmlSpace-värde som anger **xml:space**-omfånget. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) konstruktor

Initierar en ny instans av klassen [XmlParserContext](../) med de angivna [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), bas-URI, **xml:lang**, **xml:space**, kodning och dokumenttypvärdena.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) att använda för att atomisera strängar. Om detta är **nullptr** används namntabellen som användes för att konstruera **nsMgr** i stället. För mer information om atomiserade strängar, se [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) att använda för att slå upp namnrymdsinformation, eller **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Namnet på dokumenttypdeklarationen. |
| pubId | const [String](../../../system/string/)\& | Den offentliga identifieraren. |
| sysId | const [String](../../../system/string/)\& | Systemidentifieraren. |
| internalSubset | const [String](../../../system/string/)\& | Det interna DTD-delmängden. DTD-delmängden används för entitetsupplösning, inte för dokumentvalidering. |
| baseURI | const [String](../../../system/string/)\& | Bas-URI för XML-fragmentet (platsen fragmentet laddades från). |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang**-omfånget. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Ett XmlSpace-värde som anger **xml:space**-omfånget. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Ett Encoding-objekt som anger kodningsinställningen. |

## Se också

* Enum [XmlSpace](../../xmlspace/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNameTable](../../xmlnametable/)
* Klass [XmlNamespaceManager](../../xmlnamespacemanager/)
* Klass [String](../../../system/string/)
* Klass [XmlParserContext](../)
* Klass [Encoding](../../../system.text/encoding/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)