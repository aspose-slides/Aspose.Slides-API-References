---
title: XmlParserContext()
second_title: Aspose.Slides voor C++ API-referentie
description: "Initialiseert een nieuw exemplaar van de XmlParserContext klasse met de opgegeven XmlNameTable, XmlNamespaceManager, xml:lang, en xml:space waarden."
type: docs
weight: 261
url: /nl/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor

Initialiseert een nieuw exemplaar van de [XmlParserContext](../) klasse met de opgegeven [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, en **xml:space** waarden.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | De [XmlNameTable](../../xmlnametable/) die gebruikt wordt om strings te atomiseren. Als dit **nullptr** is, wordt de nametabel die gebruikt wordt om de **nsMgr** te construeren, gebruikt. Voor meer informatie over geatomiseerde strings, zie [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | De [XmlNamespaceManager](../../xmlnamespacemanager/) die gebruikt wordt om naamruimteinformatie op te zoeken, of **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | De **xml:lang**-scope. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Een XmlSpace-waarde die de **xml:space**-scope aangeeft. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlParserContext](../) klasse met de opgegeven [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space**, en codering.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | De [XmlNameTable](../../xmlnametable/) die gebruikt wordt om strings te atomiseren. Als dit **nullptr** is, wordt de nametabel die gebruikt wordt om de **nsMgr** te construeren, gebruikt. Voor meer informatie over geatomiseerde strings, zie [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | De [XmlNamespaceManager](../../xmlnamespacemanager/) die gebruikt wordt om naamruimteinformatie op te zoeken, of **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | De **xml:lang**-scope. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Een XmlSpace-waarde die de **xml:space**-scope aangeeft. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Een Encoding-object dat de coderinginstelling aangeeft. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor

Initialiseert een nieuw exemplaar van de [XmlParserContext](../) klasse met de opgegeven [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), basis-URI, **xml:lang**, **xml:space**, en documenttype-waarden.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | De [XmlNameTable](../../xmlnametable/) die gebruikt wordt om strings te atomiseren. Als dit **nullptr** is, wordt de nametabel die gebruikt wordt om de **nsMgr** te construeren, gebruikt. Voor meer informatie over geatomiseerde strings, zie [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | De [XmlNamespaceManager](../../xmlnamespacemanager/) die gebruikt wordt om naamruimteinformatie op te zoeken, of **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | De naam van de documenttype-declaratie. |
| pubId | const [String](../../../system/string/)\& | De publieke identifier. |
| sysId | const [String](../../../system/string/)\& | De systeemidentifier. |
| internalSubset | const [String](../../../system/string/)\& | De interne DTD-subset. De DTD-subset wordt gebruikt voor entiteit resolutie, niet voor documentvalidatie. |
| baseURI | const [String](../../../system/string/)\& | De basis-URI voor het XML-fragment (de locatie van waar het fragment werd geladen). |
| xmlLang | const [String](../../../system/string/)\& | De **xml:lang**-scope. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Een XmlSpace-waarde die de **xml:space**-scope aangeeft. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlParserContext](../) klasse met de opgegeven [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), basis-URI, **xml:lang**, **xml:space**, codering, en documenttype-waarden.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | De [XmlNameTable](../../xmlnametable/) die gebruikt wordt om strings te atomiseren. Als dit **nullptr** is, wordt de nametabel die gebruikt wordt om de **nsMgr** te construeren, gebruikt. Voor meer informatie over geatomiseerde strings, zie [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | De [XmlNamespaceManager](../../xmlnamespacemanager/) die gebruikt wordt om naamruimteinformatie op te zoeken, of **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | De naam van de documenttype-declaratie. |
| pubId | const [String](../../../system/string/)\& | De publieke identifier. |
| sysId | const [String](../../../system/string/)\& | De systeemidentifier. |
| internalSubset | const [String](../../../system/string/)\& | De interne DTD-subset. De DTD wordt gebruikt voor entiteit resolutie, niet voor documentvalidatie. |
| baseURI | const [String](../../../system/string/)\& | De basis-URI voor het XML-fragment (de locatie van waar het fragment werd geladen). |
| xmlLang | const [String](../../../system/string/)\& | De **xml:lang**-scope. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Een XmlSpace-waarde die de **xml:space**-scope aangeeft. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Een Encoding-object dat de codering aangeeft. |

## Zie ook

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNameTable](../../xmlnametable/)
* Klasse [XmlNamespaceManager](../../xmlnamespacemanager/)
* Klasse [String](../../../system/string/)
* Klasse [XmlParserContext](../)
* Klasse [Encoding](../../../system.text/encoding/)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)