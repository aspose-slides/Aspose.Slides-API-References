---
title: ValidateElement()
second_title: Aspose.Slides pro C++ API Referenční příručka
description: Ověřuje prvek v aktuálním kontextu.
type: docs
weight: 131
url: /cs/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String&, const String&, const SharedPtr<XmlSchemaInfo>&) metoda

Ověřuje prvek v aktuálním kontextu.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | Místní název prvku, který má být ověřen. |
| namespaceUri | const [String](../../../system/string/)& | URI jmenného prostoru prvku, který má být ověřen. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaInfo](../../xmlschemainfo/)>& | Objekt [XmlSchemaInfo](../../xmlschemainfo/), jehož vlastnosti jsou nastaveny při úspěšném ověření názvu prvku. Tento parametr může být **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String&, const String&, const SharedPtr<XmlSchemaInfo>&, const String&, const String&, const String&, const String&) metoda

Ověřuje prvek v aktuálním kontextu s určenými hodnotami atributů **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** a **xsi:NoNamespaceSchemaLocation**.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | Místní název prvku, který má být ověřen. |
| namespaceUri | const [String](../../../system/string/)& | URI jmenného prostoru prvku, který má být ověřen. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaInfo](../../xmlschemainfo/)>& | Objekt [XmlSchemaInfo](../../xmlschemainfo/), jehož vlastnosti jsou nastaveny při úspěšném ověření názvu prvku. Tento parametr může být **nullptr**. |
| xsiType | const [String](../../../system/string/)& | Hodnota atributu **xsi:Type** prvku. Tento parametr může být **nullptr**. |
| xsiNil | const [String](../../../system/string/)& | Hodnota atributu **xsi:Nil** prvku. Tento parametr může být **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)& | Hodnota atributu **xsi:SchemaLocation** prvku. Tento parametr může být **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)& | Hodnota atributu **xsi:NoNamespaceSchemaLocation** prvku. Tento parametr může být **nullptr**. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [XmlSchemaInfo](../../xmlschemainfo/)
* Třída [XmlSchemaValidator](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)