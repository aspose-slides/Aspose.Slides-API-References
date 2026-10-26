---
title: XmlParserContext()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Inicjalizuje nową instancję klasy XmlParserContext z określonymi XmlNameTable, XmlNamespaceManager, xml:lang i xml:space."
type: docs
weight: 261
url: /pl/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor

Inicjalizuje nową instancję klasy [XmlParserContext](../) z określonymi [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** i **xml:space**.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) używany do atomizacji ciągów znaków. Jeśli jest **nullptr**, używana jest tabela nazw, która została użyta do utworzenia **nsMgr**. Aby uzyskać więcej informacji o atomizowanych ciągach znaków, zobacz [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) używany do wyszukiwania informacji o przestrzeni nazw lub **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Zakres **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Wartość XmlSpace wskazująca zakres **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Inicjalizuje nową instancję klasy [XmlParserContext](../) z określonymi [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** i kodowaniem.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) używany do atomizacji ciągów znaków. Jeśli jest **nullptr**, używana jest tabela nazw, która została użyta do utworzenia **nsMgr**. Aby uzyskać więcej informacji o atomizowanych ciągach znaków, zobacz [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) używany do wyszukiwania informacji o przestrzeni nazw lub **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Zakres **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Wartość XmlSpace wskazująca zakres **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Obiekt Encoding wskazujący ustawienie kodowania. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor

Inicjalizuje nową instancję klasy [XmlParserContext](../) z określonymi [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), bazowym URI, **xml:lang**, **xml:space** oraz wartościami typu dokumentu.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) używany do atomizacji ciągów znaków. Jeśli jest **nullptr**, używana jest tabela nazw, która została użyta do utworzenia **nsMgr**. Aby uzyskać więcej informacji o atomizowanych ciągach znaków, zobacz [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) używany do wyszukiwania informacji o przestrzeni nazw lub **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Nazwa deklaracji typu dokumentu. |
| pubId | const [String](../../../system/string/)\& | Publiczny identyfikator. |
| sysId | const [String](../../../system/string/)\& | Identyfikator systemowy. |
| internalSubset | const [String](../../../system/string/)\& | Wewnętrzny podzbiór DTD. Podzbiór DTD jest używany do rozwiązywania encji, nie do walidacji dokumentu. |
| baseURI | const [String](../../../system/string/)\& | Podstawowy URI dla fragmentu XML (lokalizacja, z której fragment został wczytany). |
| xmlLang | const [String](../../../system/string/)\& | Zakres **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Wartość XmlSpace wskazująca zakres **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Inicjalizuje nową instancję klasy [XmlParserContext](../) z określonymi [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), bazowym URI, **xml:lang**, **xml:space**, kodowaniem i wartościami typu dokumentu.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) używany do atomizacji ciągów znaków. Jeśli jest **nullptr**, używana jest tabela nazw, która została użyta do utworzenia **nsMgr**. Aby uzyskać więcej informacji o atomizowanych ciągach znaków, zobacz [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) używany do wyszukiwania informacji o przestrzeni nazw lub **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Nazwa deklaracji typu dokumentu. |
| pubId | const [String](../../../system/string/)\& | Publiczny identyfikator. |
| sysId | const [String](../../../system/string/)\& | Identyfikator systemowy. |
| internalSubset | const [String](../../../system/string/)\& | Wewnętrzny podzbiór DTD. DTD jest używany do rozwiązywania encji, nie do walidacji dokumentu. |
| baseURI | const [String](../../../system/string/)\& | Podstawowy URI dla fragmentu XML (lokalizacja, z której fragment został wczytany). |
| xmlLang | const [String](../../../system/string/)\& | Zakres **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Wartość XmlSpace wskazująca zakres **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Obiekt Encoding wskazujący ustawienie kodowania. |

## Zobacz także

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)