---
title: GetElementsByTagName()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací XmlNodeList obsahující seznam všech podřízených elementů, které odpovídají zadanému názvu.
type: docs
weight: 443
url: /cs/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) metoda

Vrací [XmlNodeList](../../xmlnodelist/) obsahující seznam všech podřízených elementů, které odpovídají zadanému názvu.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název k porovnání. Je porovnáván s hodnotou **get_Name** odpovídajícího uzlu. Speciální hodnota **"*"** odpovídá všem tagům. |

### Návratová hodnota

[XmlNodeList](../../xmlnodelist/) obsahující seznam všech odpovídajících uzlů. Pokud žádný uzel neodpovídá **name**, bude vrácená kolekce prázdná.

## XmlDocument::GetElementsByTagName(String, String) metoda

Vrací [XmlNodeList](../../xmlnodelist/) obsahující seznam všech podřízených elementů, které odpovídají zadaným [XmlDocument::get_LocalName](../get_localname/) a [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | LocalName k porovnání. Speciální hodnota **"*"** odpovídá všem tagům. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI k porovnání. |

### Návratová hodnota

[XmlNodeList](../../xmlnodelist/) obsahující seznam všech odpovídajících uzlů. Pokud žádný uzel neodpovídá zadaným **localName** a **namespaceURI**, bude vrácená kolekce prázdná.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNodeList](../../xmlnodelist/)
* Třída [String](../../../system/string/)
* Třída [XmlDocument](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)