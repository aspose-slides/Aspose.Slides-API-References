---
title: ValidateAttribute()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Validuje název atributu, URI jmenného prostoru a hodnotu v kontextu aktuálního elementu.
type: docs
weight: 144
url: /cs/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) metoda


Validuje název atributu, URI jmenného prostoru a hodnotu v kontextu aktuálního elementu.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Místní název atributu k validaci. |
| namespaceUri | const [String](../../../system/string/)\& | URI jmenného prostoru atributu, který se má ověřit. |
| attributeValue | const [String](../../../system/string/)\& | Hodnota atributu k validaci. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Objekt [XmlSchemaInfo](../../xmlschemainfo/), jehož vlastnosti jsou nastaveny při úspěšné validaci atributu. Tento parametr může být **nullptr**. |

### Návratová hodnota

Hodnota validovaného atributu.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) metoda


Validuje název atributu, URI jmenného prostoru a hodnotu v kontextu aktuálního elementu.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Místní název atributu k validaci. |
| namespaceUri | const [String](../../../system/string/)\& | URI jmenného prostoru atributu, který se má ověřit. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Callback XmlValueGetter použitý k předání hodnoty atributu jako typu kompatibilního s XML [Schema](../../) Definition Language (XSD) typem atributu. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Objekt [XmlSchemaInfo](../../xmlschemainfo/), jehož vlastnosti jsou nastaveny při úspěšné validaci atributu. Tento parametr může být **nullptr**. |

### Návratová hodnota

Hodnota validovaného atributu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Třída [Object](../../../system/object/)
* Třída [String](../../../system/string/)
* Třída [XmlSchemaInfo](../../xmlschemainfo/)
* Třída [XmlSchemaValidator](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)