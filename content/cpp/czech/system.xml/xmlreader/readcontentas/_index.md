---
title: ReadContentAs()
second_title: Aspose.Slides pro C++ API Reference
description: Načte obsah jako objekt zadaného typu.
type: docs
weight: 456
url: /cs/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

Načte obsah jako objekt zadaného typu.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Parametry

| Parametr | Typ | Popis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ hodnoty, která má být vrácena. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Objekt [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), který se používá k rozlišení jakýchkoli předpon jmenných prostorů souvisejících s konverzí typu. Například lze tento objekt použít při převodu objektu [XmlQualifiedName](../../xmlqualifiedname/) na **xs:string**. Tato hodnota může být **nullptr**. |

### Návratová hodnota

Slučený textový obsah nebo hodnota atributu převedená na požadovaný typ.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)