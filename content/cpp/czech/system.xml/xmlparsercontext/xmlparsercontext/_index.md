---
title: XmlParserContext()
second_title: Aspose.Slides pro C++ API Reference
description: "Inicializuje novou instanci třídy XmlParserContext se zadanými hodnotami XmlNameTable, XmlNamespaceManager, xml:lang a xml:space."
type: docs
weight: 261
url: /cs/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) konstruktor


Inicializuje novou instanci třídy [XmlParserContext](../) s určenými hodnotami [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** a **xml:space**.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) používaná k atomizaci řetězců. Pokud je **nullptr**, použije se tabulka názvů použitá při konstrukci **nsMgr**. Další informace o atomizovaných řetězcích najdete v [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) používaná k vyhledávání informací o jmenných prostorech, nebo **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Oblast **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Hodnota XmlSpace určující oblast **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) konstruktor


Inicializuje novou instanci třídy [XmlParserContext](../) s určenými hodnotami [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** a kódováním.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) používaná k atomizaci řetězců. Pokud je **nullptr**, použije se tabulka názvů použitá při konstrukci **nsMgr**. Další informace o atomizovaných řetězcích najdete v [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) používaná k vyhledávání informací o jmenných prostorech, nebo **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Oblast **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Hodnota XmlSpace určující oblast **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Objekt Encoding určující nastavení kódování. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) konstruktor


Inicializuje novou instanci třídy [XmlParserContext](../) s určenými hodnotami [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), základní URI, **xml:lang**, **xml:space** a hodnotami typu dokumentu.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) používaná k atomizaci řetězců. Pokud je **nullptr**, použije se tabulka názvů použitá při konstrukci **nsMgr**. Další informace o atomizovaných řetězcích najdete v [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) používaná k vyhledávání informací o jmenných prostorech, nebo **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Název deklarace typu dokumentu. |
| pubId | const [String](../../../system/string/)\& | Veřejný identifikátor. |
| sysId | const [String](../../../system/string/)\& | Systémový identifikátor. |
| internalSubset | const [String](../../../system/string/)\& | Interní podmnožina DTD. Podmnožina DTD se používá pro řešení entit, nikoli pro validaci dokumentu. |
| baseURI | const [String](../../../system/string/)\& | Základní URI pro fragment XML (umístění, odkud byl fragment načten). |
| xmlLang | const [String](../../../system/string/)\& | Oblast **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Hodnota XmlSpace určující oblast **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) konstruktor


Inicializuje novou instanci třídy [XmlParserContext](../) s určenými hodnotami [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), základní URI, **xml:lang**, **xml:space**, kódováním a hodnotami typu dokumentu.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) používá k atomizaci řetězců. Pokud je **nullptr**, použije se tabulka názvů použitá při konstrukci **nsMgr**. Další informace o atomizovaných řetězcích najdete v [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) používá k vyhledávání informací o jmenných prostorech, nebo **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Název deklarace typu dokumentu. |
| pubId | const [String](../../../system/string/)\& | Veřejný identifikátor. |
| sysId | const [String](../../../system/string/)\& | Systémový identifikátor. |
| internalSubset | const [String](../../../system/string/)\& | Interní podmnožina DTD. DTD se používá pro řešení entit, nikoli pro validaci dokumentu. |
| baseURI | const [String](../../../system/string/)\& | Základní URI pro fragment XML (umístění, odkud byl fragment načten). |
| xmlLang | const [String](../../../system/string/)\& | Oblast **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Hodnota XmlSpace určující oblast **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Objekt Encoding určující nastavení kódování. |

## Viz také

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNameTable](../../xmlnametable/)
* Třída [XmlNamespaceManager](../../xmlnamespacemanager/)
* Třída [String](../../../system/string/)
* Třída [XmlParserContext](../)
* Třída [Encoding](../../../system.text/encoding/)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)