---
title: ReadContentAs()
second_title: Aspose.Slides a C++ API referenciához
description: A tartalmat a megadott típusú objektumként olvassa.
type: docs
weight: 456
url: /hu/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metódus

A tartalmat a megadott típusú objektumként olvassa.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | A visszaadandó érték típusa. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Egy [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) objektum, amelyet a típuskonverzióval kapcsolatos névtér előtagok feloldására használnak. Például akkor használható, amikor egy [XmlQualifiedName](../../xmlqualifiedname/) objektumot **xs:string**-re konvertálunk. Ez az érték lehet **nullptr**. |

### Visszatérési érték

A kért típusra konvertált összefűzött szövegtartalom vagy attribútumérték.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)