---
title: ChangeType()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konwertuje podaną wartość, której typ jest jedną z prawidłowych reprezentacji typu schematu XML reprezentowanego przez XmlSchemaDatatype, na określony w czasie wykonywania typ.
type: docs
weight: 66
url: /pl/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) metoda

Konwertuje podaną wartość, której typ jest jedną z prawidłowych reprezentacji typu schematu XML reprezentowanego przez [XmlSchemaDatatype](../), na typ określony w czasie wykonywania.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Wartość wejściowa do konwersji na określony typ. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Typ docelowy, na który ma zostać skonwertowana wartość wejściowa. |

### Wartość zwracana

Konwertowana wartość wejściowa.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda

Konwertuje podaną wartość, której typ jest jedną z prawidłowych reprezentacji typu schematu XML reprezentowanego przez [XmlSchemaDatatype](../), na typ określony w czasie wykonywania przy użyciu [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), jeśli [XmlSchemaDatatype](../) reprezentuje typ **xs:QName** lub typ pochodny.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Wartość wejściowa do konwersji na określony typ. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Typ docelowy, na który ma zostać skonwertowana wartość wejściowa. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) używany do rozwiązywania prefiksów przestrzeni nazw. Ma zastosowanie tylko wtedy, gdy [XmlSchemaDatatype](../) reprezentuje typ **xs:QName** lub typ pochodny. |

### Wartość zwracana

Konwertowana wartość wejściowa.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [XmlSchemaDatatype](../)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)