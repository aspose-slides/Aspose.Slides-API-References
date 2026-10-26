---
title: ValidateAttribute()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Waliduje nazwę atrybutu, URI przestrzeni nazw oraz wartość w bieżącym kontekście elementu.
type: docs
weight: 144
url: /pl/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) metoda

Waliduje nazwę atrybutu, URI przestrzeni nazw oraz wartość w bieżącym kontekście elementu.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Lokalna nazwa atrybutu do walidacji. |
| namespaceUri | const [String](../../../system/string/)\& | URI przestrzeni nazw atrybutu do walidacji. |
| attributeValue | const [String](../../../system/string/)\& | Wartość atrybutu do walidacji. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Obiekt [XmlSchemaInfo](../../xmlschemainfo/), którego właściwości są ustawiane po pomyślnej walidacji atrybutu. Ten parametr może być **nullptr**. |

### Wartość zwracana

Wartość zwalidowanego atrybutu.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) metoda

Waliduje nazwę atrybutu, URI przestrzeni nazw oraz wartość w bieżącym kontekście elementu.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Lokalna nazwa atrybutu do walidacji. |
| namespaceUri | const [String](../../../system/string/)\& | URI przestrzeni nazw atrybutu do walidacji. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Wywołanie zwrotne XmlValueGetter używane do przekazania wartości atrybutu jako typ zgodny z typem XML [Schema](../../) Definition Language (XSD) atrybutu. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Obiekt [XmlSchemaInfo](../../xmlschemainfo/), którego właściwości są ustawiane po pomyślnej walidacji atrybutu. Ten parametr może być **nullptr**. |

### Wartość zwracana

Wartość zwalidowanego atrybutu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Klasa [Object](../../../system/object/)
* Klasa [String](../../../system/string/)
* Klasa [XmlSchemaInfo](../../xmlschemainfo/)
* Klasa [XmlSchemaValidator](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)