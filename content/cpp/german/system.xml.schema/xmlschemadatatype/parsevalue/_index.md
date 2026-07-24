---
title: ParseValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, validiert sie den angegebenen string gegenüber einem integrierten oder benutzerdefinierten einfachen Typ.
type: docs
weight: 53
url: /de/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) Methode


Wenn in einer abgeleiteten Klasse überschrieben, validiert die angegebene **string** gegenüber einem eingebauten oder benutzerdefinierten einfachen Typ.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| s | [String](../../../system/string/) | Die **string** zur Validierung gegen den einfachen Typ. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | Der [XmlNameTable](../../../system.xml/xmlnametable/) zur Verwendung für die Atomisierung beim Parsen der **string**, wenn dieses [XmlSchemaDatatype](../)-Objekt den Typ **xs:NCName** darstellt. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Der [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt zur Verwendung beim Parsen der **string**, wenn dieses [XmlSchemaDatatype](../)-Objekt den Typ **xs:QName** darstellt. |

### Rückgabewert

Ein [Object](../../../system/object/), das sicher in den von dem Aufruf [XmlSchemaDatatype::get_ValueType](../get_valuetype/) zurückgegebenen Typ umgewandelt werden kann.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)