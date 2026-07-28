---
title: ValidateElement()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Waliduje element w bieżącym kontekście.
type: docs
weight: 131
url: /pl/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String&, const String&, const SharedPtr<XmlSchemaInfo>&) method

Waliduje element w bieżącym kontekście.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | Lokalna nazwa elementu do walidacji. |
| namespaceUri | const [String](../../../system/string/)& | URI przestrzeni nazw elementu do walidacji. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaInfo](../../xmlschemainfo/)>& | Obiekt [XmlSchemaInfo](../../xmlschemainfo/) którego właściwości są ustawiane po pomyślnej walidacji nazwy elementu. Ten parametr może być **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String&, const String&, const SharedPtr<XmlSchemaInfo>&, const String&, const String&, const String&, const String&) method

Waliduje element w bieżącym kontekście z określonymi wartościami atrybutów **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** i **xsi:NoNamespaceSchemaLocation**.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | Lokalna nazwa elementu do walidacji. |
| namespaceUri | const [String](../../../system/string/)& | URI przestrzeni nazw elementu do walidacji. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaInfo](../../xmlschemainfo/)>& | Obiekt [XmlSchemaInfo](../../xmlschemainfo/) którego właściwości są ustawiane po pomyślnej walidacji nazwy elementu. Ten parametr może być **nullptr**. |
| xsiType | const [String](../../../system/string/)& | Wartość atrybutu **xsi:Type** elementu. Ten parametr może być **nullptr**. |
| xsiNil | const [String](../../../system/string/)& | Wartość atrybutu **xsi:Nil** elementu. Ten parametr może być **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)& | Wartość atrybutu **xsi:SchemaLocation** elementu. Ten parametr może być **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)& | Wartość atrybutu **xsi:NoNamespaceSchemaLocation** elementu. Ten parametr może być **nullptr**. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)