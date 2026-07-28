---
title: XmlSchemaValidator()
second_title: Aspose.Slides C++ API referencia
description: Inicializál egy új példányt az XmlSchemaValidator osztályból.
type: docs
weight: 92
url: /hu/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor


Inicializál egy új példányt a [XmlSchemaValidator](../) osztályból.

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | [XmlNameTable](../../../system.xml/xmlnametable/) objektum, amely elemek és attribútumok neveit atomizált karakterláncokként tartalmazza. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | [XmlSchemaSet](../../xmlschemaset/) objektum, amely az XML [Schema](../../) Definition Language (XSD) sémákat tartalmazza, amelyeket a validáláshoz használnak. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum, amely a validálás során felmerülő névterek feloldására szolgál. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Az XmlSchemaValidationFlags érték, amely a sémaellenőrzési beállításokat határozza meg. |

## Lásd még

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNameTable](../../../system.xml/xmlnametable/)
* Osztály [XmlSchemaSet](../../xmlschemaset/)
* Osztály [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Osztály [XmlSchemaValidator](../)
* Névtere [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)