---
title: ParseValue()
second_title: Aspose.Slides C++ API-referencia
description: Ha egy származtatott osztályban felül van definiálva, ellenőrzi a megadott stringet egy beépített vagy felhasználó által definiált egyszerű típus alapján.
type: docs
weight: 53
url: /hu/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) metódus

Ha egy származtatott osztályban felül van definiálva, ellenőrzi a megadott **string**-et egy beépített vagy felhasználó által definiált egyszerű típus szerint.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | [String](../../../system/string/) | A **string**, amelyet az egyszerű típus ellen kell ellenőrizni. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | Az [XmlNameTable](../../../system.xml/xmlnametable/), amelyet az atomizáláshoz használnak a **string** feldolgozása során, ha ez a [XmlSchemaDatatype](../) objektum a **xs:NCName** típust képviseli. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | A [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum, amelyet a **string** feldolgozása során használnak, ha ez a [XmlSchemaDatatype](../) objektum a **xs:QName** típust képviseli. |

### Visszatérési érték

Egy [Object](../../../system/object/) amely biztonságosan átkonvertálható a [XmlSchemaDatatype::get_ValueType](../get_valuetype/) hívás által visszaadott típusra.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [String](../../../system/string/)
* Osztály [XmlNameTable](../../../system.xml/xmlnametable/)
* Osztály [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Osztály [XmlSchemaDatatype](../)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)