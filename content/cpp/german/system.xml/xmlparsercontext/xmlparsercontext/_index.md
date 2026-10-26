---
title: XmlParserContext()
second_title: Aspose.Slides für C++ API-Referenz
description: "Initialisiert eine neue Instanz der XmlParserContext-Klasse mit den angegebenen XmlNameTable-, XmlNamespaceManager-, xml:lang- und xml:space-Werten."
type: docs
weight: 261
url: /de/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) Konstruktor


Initialisiert eine neue Instanz der [XmlParserContext](../) Klasse mit den angegebenen [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** und **xml:space** Werten.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Der [XmlNameTable](../../xmlnametable/) zum Atomisieren von Zeichenketten. Falls dies **nullptr** ist, wird stattdessen die zum Erzeugen des **nsMgr** verwendete Namenstabelle benutzt. Siehe [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Der [XmlNamespaceManager](../../xmlnamespacemanager/) zum Nachschlagen von Namespace-Informationen oder **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Der **xml:lang**-Bereich. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Ein XmlSpace-Wert, der den **xml:space**-Bereich angibt. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) Konstruktor


Initialisiert eine neue Instanz der [XmlParserContext](../) Klasse mit den angegebenen [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** und der Kodierung.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Der [XmlNameTable](../../xmlnametable/) zum Atomisieren von Zeichenketten. Falls dies **nullptr** ist, wird stattdessen die zum Erzeugen des **nsMgr** verwendete Namenstabelle benutzt. Siehe [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Der [XmlNamespaceManager](../../xmlnamespacemanager/) zum Nachschlagen von Namespace-Informationen oder **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Der **xml:lang**-Bereich. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Ein XmlSpace-Wert, der den **xml:space**-Bereich angibt. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Ein Encoding-Objekt, das die Kodierungseinstellung angibt. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) Konstruktor


Initialisiert eine neue Instanz der [XmlParserContext](../) Klasse mit den angegebenen [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), Basis-URI, **xml:lang**, **xml:space** und Dokumenttyp-Werten.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Der [XmlNameTable](../../xmlnametable/) zum Atomisieren von Zeichenketten. Falls dies **nullptr** ist, wird stattdessen die zum Erzeugen des **nsMgr** verwendete Namenstabelle benutzt. Siehe [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Der [XmlNamespaceManager](../../xmlnamespacemanager/) zum Nachschlagen von Namespace-Informationen oder **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Der Name der Dokumenttyp-Deklaration. |
| pubId | const [String](../../../system/string/)\& | Der öffentliche Bezeichner. |
| sysId | const [String](../../../system/string/)\& | Der Systembezeichner. |
| internalSubset | const [String](../../../system/string/)\& | Der interne DTD-Teil. Der DTD-Teil wird zur Entitätauflösung verwendet, nicht zur Dokumentvalidierung. |
| baseURI | const [String](../../../system/string/)\& | Der Basis-URI für das XML-Fragment (der Ort, von dem das Fragment geladen wurde). |
| xmlLang | const [String](../../../system/string/)\& | Der **xml:lang**-Bereich. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Ein XmlSpace-Wert, der den **xml:space**-Bereich angibt. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) Konstruktor


Initialisiert eine neue Instanz der [XmlParserContext](../) Klasse mit den angegebenen [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), Basis-URI, **xml:lang**, **xml:space**, Kodierung und Dokumenttyp-Werten.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Der [XmlNameTable](../../xmlnametable/) zum Atomisieren von Zeichenketten. Falls dies **nullptr** ist, wird stattdessen die zum Erzeugen des **nsMgr** verwendete Namenstabelle benutzt. Siehe [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Der [XmlNamespaceManager](../../xmlnamespacemanager/) zum Nachschlagen von Namespace-Informationen oder **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Der Name der Dokumenttyp-Deklaration. |
| pubId | const [String](../../../system/string/)\& | Der öffentliche Bezeichner. |
| sysId | const [String](../../../system/string/)\& | Der Systembezeichner. |
| internalSubset | const [String](../../../system/string/)\& | Der interne DTD-Teil. Der DTD wird zur Entitätauflösung verwendet, nicht zur Dokumentvalidierung. |
| baseURI | const [String](../../../system/string/)\& | Der Basis-URI für das XML-Fragment (der Ort, von dem das Fragment geladen wurde). |
| xmlLang | const [String](../../../system/string/)\& | Der **xml:lang**-Bereich. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Ein XmlSpace-Wert, der den **xml:space**-Bereich angibt. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Ein Encoding-Objekt, das die Kodierungseinstellung angibt. |

## Siehe auch

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNameTable](../../xmlnametable/)
* Klasse [XmlNamespaceManager](../../xmlnamespacemanager/)
* Klasse [String](../../../system/string/)
* Klasse [XmlParserContext](../)
* Klasse [Encoding](../../../system.text/encoding/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)