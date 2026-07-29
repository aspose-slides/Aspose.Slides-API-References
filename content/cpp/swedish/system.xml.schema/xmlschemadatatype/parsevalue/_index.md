---
title: ParseValue()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en härledd klass validerar den den angivna stringen mot en inbyggd eller användardefinierad enkel typ.
type: docs
weight: 53
url: /sv/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) metod

När den åsidosätts i en härledd klass validerar den angivna **string** mot en inbyggd eller användardefinierad enkel typ.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | [String](../../../system/string/) | Den **string** som ska valideras mot den enkla typen. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | Den [XmlNameTable](../../../system.xml/xmlnametable/) som ska användas för atomisering vid parsning av **string** om detta [XmlSchemaDatatype](../)-objekt representerar **xs:NCName**-typen. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Det [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som ska användas vid parsning av **string** om detta [XmlSchemaDatatype](../)-objekt representerar **xs:QName**-typen. |

### Returvärde

Ett [Object](../../../system/object/) som säkert kan kastas till typen som returneras av [XmlSchemaDatatype::get_ValueType](../get_valuetype/)-anropet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [String](../../../system/string/)
* Klass [XmlNameTable](../../../system.xml/xmlnametable/)
* Klass [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klass [XmlSchemaDatatype](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)