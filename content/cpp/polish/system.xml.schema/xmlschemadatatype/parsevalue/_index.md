---
title: ParseValue()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Gdy zostanie przesłonięta w klasie pochodnej, waliduje określony ciąg znaków względem wbudowanego lub definiowanego przez użytkownika typu prostego.
type: docs
weight: 53
url: /pl/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) metoda


Gdy jest przesłonięta w klasie pochodnej, waliduje **string** określony w odniesieniu do wbudowanego lub definiowanego przez użytkownika typu prostego.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | [String](../../../system/string/) | **string** do walidacji względem typu prostego. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | [XmlNameTable](../../../system.xml/xmlnametable/) używany do atomizacji podczas parsowania **string**, jeśli ten obiekt [XmlSchemaDatatype](../) reprezentuje typ **xs:NCName**. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) używany podczas parsowania **string**, jeśli ten obiekt [XmlSchemaDatatype](../) reprezentuje typ **xs:QName**. |

### Wartość zwracana

[Object](../../../system/object/) który może być bezpiecznie rzutowany na typ zwracany przez wywołanie [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [String](../../../system/string/)
* Klasa [XmlNameTable](../../../system.xml/xmlnametable/)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasa [XmlSchemaDatatype](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)