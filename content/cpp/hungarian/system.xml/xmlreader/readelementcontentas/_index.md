---
title: ReadElementContentAs()
second_title: Aspose.Slides C++ API referenciája
description: Beolvassa az elem tartalmát a kért típusban.
type: docs
weight: 586
url: /hu/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metódus

Beolvassa az elem tartalmát a kért típusban.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | A visszaadandó érték típusa. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Egy [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) objektum, amelyet a típuskonverzióval kapcsolatos névtérelőtagok feloldására használnak. |

### Visszatérési érték

Az elem tartalma, amely a kért típusú objektummá van konvertálva.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) metódus

Ellenőrzi, hogy a megadott helyi név és névtér-URI megegyezik-e az aktuális elemével, majd beolvassa az elem tartalmát a kért típusban.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | A visszaadandó érték típusa. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Egy [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) objektum, amelyet a típuskonverzióval kapcsolatos névtérelőtagok feloldására használnak. |
| localName | [String](../../../system/string/) | Az elem helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az elem névtér URI-ja. |

### Visszatérési érték

Az elem tartalma, amely a kért típusú objektummá van konvertálva.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Osztály [XmlReader](../)
* Osztály [String](../../../system/string/)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)