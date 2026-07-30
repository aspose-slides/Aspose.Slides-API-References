---
title: ReadElementContentAs()
second_title: Aspose.Slides pro C++ API Reference
description: Čte obsah prvku jako požadovaný typ.
type: docs
weight: 586
url: /cs/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda


Čte obsah prvku jako požadovaný typ.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ hodnoty, která má být vrácena. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Objekt [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), který se používá k rozlišení jakýchkoli předpon jmenných prostorů souvisejících s konverzí typů. |

### Návratová hodnota

Obsah prvku převedený na objekt požadovaného typu.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) metoda


Kontroluje, že zadaný místní název a URI jmenného prostoru odpovídají aktuálnímu prvku, poté čte obsah prvku jako požadovaný typ.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ hodnoty, která má být vrácena. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Objekt [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), který se používá k rozlišení jakýchkoli předpon jmenných prostorů souvisejících s konverzí typů. |
| localName | [String](../../../system/string/) | Místní název prvku. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru prvku. |

### Návratová hodnota

Obsah prvku převedený na objekt požadovaného typu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Třída [XmlReader](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)