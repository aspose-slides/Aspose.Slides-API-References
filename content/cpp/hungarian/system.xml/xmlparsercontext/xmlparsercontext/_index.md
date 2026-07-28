---
title: XmlParserContext()
second_title: Aspose.Slides for C++ API Referenciája
description: "Inicializál egy új példányt az XmlParserContext osztályból a megadott XmlNameTable, XmlNamespaceManager, xml:lang és xml:space értékekkel."
type: docs
weight: 261
url: /hu/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) konstruktor


Inicializál egy új példányt a [XmlParserContext](../) osztályban a megadott [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, és **xml:space** értékekkel.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | A [XmlNameTable](../../xmlnametable/) a karakterláncok atomizálásához. Ha ez **nullptr**, a **nsMgr** létrehozásához használt névtábla lesz használva helyette. További információ az atomizált karakterláncokról: [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | A [XmlNamespaceManager](../../xmlnamespacemanager/) névtér-információk kereséséhez, vagy **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | A **xml:lang** hatókör. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Egy XmlSpace érték, amely a **xml:space** hatókört jelzi. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) konstruktor


Inicializál egy új példányt a [XmlParserContext](../) osztályban a megadott [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space**, és kódolás értékekkel.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | A [XmlNameTable](../../xmlnametable/) a karakterláncok atomizálásához. Ha ez **nullptr**, a **nsMgr** létrehozásához használt névtábla lesz használva helyette. További információ az atomizált karakterláncokról: [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | A [XmlNamespaceManager](../../xmlnamespacemanager/) névtérinformációk kereséséhez, vagy **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | A **xml:lang** hatókör. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Egy XmlSpace érték, amely a **xml:space** hatókört jelzi. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Egy Encoding objektum, amely a kódolási beállítást jelzi. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) konstruktor


Inicializál egy új példányt a [XmlParserContext](../) osztályban a megadott [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), alap URI, **xml:lang**, **xml:space**, és dokumentumtípus értékekkel.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | A [XmlNameTable](../../xmlnametable/) a karakterláncok atomizálásához. Ha ez **nullptr**, a **nsMgr** létrehozásához használt névtábla lesz használva helyette. További információ az atomizált karakterláncokról: [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | A [XmlNamespaceManager](../../xmlnamespacemanager/) névtérinformációk kereséséhez, vagy **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | A dokumentumtípus deklaráció neve. |
| pubId | const [String](../../../system/string/)\& | A nyilvános azonosító. |
| sysId | const [String](../../../system/string/)\& | A rendszerazonosító. |
| internalSubset | const [String](../../../system/string/)\& | A belső DTD részhalmaz. A DTD részhalmaz az entitások feloldására szolgál, nem a dokumentum validálására. |
| baseURI | const [String](../../../system/string/)\& | Az XML töredék alap URI-ja (az a hely, ahonnan a töredék betöltődött). |
| xmlLang | const [String](../../../system/string/)\& | A **xml:lang** hatókör. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Egy XmlSpace érték, amely a **xml:space** hatókört jelzi. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) konstruktor


Inicializál egy új példányt a [XmlParserContext](../) osztályban a megadott [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), alap URI, **xml:lang**, **xml:space**, kódolás és dokumentumtípus értékekkel.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | A [XmlNameTable](../../xmlnametable/) a karakterláncok atomizálásához. Ha ez **nullptr**, a **nsMgr** létrehozásához használt névtábla lesz használva helyette. További információ az atomizált karakterláncokról: [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | A [XmlNamespaceManager](../../xmlnamespacemanager/) névtérinformációk kereséséhez, vagy **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | A dokumentumtípus deklaráció neve. |
| pubId | const [String](../../../system/string/)\& | A nyilvános azonosító. |
| sysId | const [String](../../../system/string/)\& | A rendszerazonosító. |
| internalSubset | const [String](../../../system/string/)\& | A belső DTD részhalmaz. A DTD az entitások feloldására szolgál, nem a dokumentum validálására. |
| baseURI | const [String](../../../system/string/)\& | Az XML töredék alap URI-ja (az a hely, ahonnan a töredék betöltődött). |
| xmlLang | const [String](../../../system/string/)\& | A **xml:lang** hatókör. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Egy XmlSpace érték, amely a **xml:space** hatókört jelzi. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Egy Encoding objektum, amely a kódolási beállítást jelzi. |

## Lásd még

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNameTable](../../xmlnametable/)
* Osztály [XmlNamespaceManager](../../xmlnamespacemanager/)
* Osztály [String](../../../system/string/)
* Osztály [XmlParserContext](../)
* Osztály [Encoding](../../../system.text/encoding/)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)