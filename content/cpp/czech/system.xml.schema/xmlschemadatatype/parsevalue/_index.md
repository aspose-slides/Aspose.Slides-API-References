---
title: ParseValue()
second_title: Aspose.Slides pro C++ API Reference
description: Když je v odvozené třídě přepsána, ověří string uvedený oproti vestavěnému nebo uživatelem definovanému jednoduchému typu.
type: docs
weight: 53
url: /cs/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) method

Při přepsání v odvozené třídě ověřuje zadaný **string** oproti vestavěnému nebo uživatelem definovanému jednoduchému typu.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | [String](../../../system/string/) | **string**, který se má ověřit vůči jednoduchému typu. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | [XmlNameTable](../../../system.xml/xmlnametable/) používaný pro atomizaci při parsování **string**, pokud tento objekt [XmlSchemaDatatype](../) představuje typ **xs:NCName**. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objekt používaný při parsování **string**, pokud tento objekt [XmlSchemaDatatype](../) představuje typ **xs:QName**. |

### Návratová hodnota

[Object](../../../system/object/) lze bezpečně převést na typ vrácený voláním [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [String](../../../system/string/)
* Třída [XmlNameTable](../../../system.xml/xmlnametable/)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Třída [XmlSchemaDatatype](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)