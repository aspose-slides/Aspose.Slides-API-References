---
title: ValueAs()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a validált XML elem vagy attribútum értékét a megadott típusban, az IXmlNamespaceResolver objektum használatával, amely a névtér-előtagok feloldására szolgál.
type: docs
weight: 144
url: /hu/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metódus

Visszaadja a validált XML elem vagy attribútum értékét a megadott típusban, a [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum használatával, amely a névtér-előtagok feloldására szolgál.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | A típus, amiben a validált XML elem vagy attribútum értékét vissza kell adni. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum, amely a névtér-előtagok feloldására szolgál. |

### Visszatérési érték

A validált XML elem vagy attribútum értéke a kért típusban.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Osztály [XmlAtomicValue](../)
* Névterület [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)