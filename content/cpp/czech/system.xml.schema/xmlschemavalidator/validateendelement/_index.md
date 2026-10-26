---
title: ValidateEndElement()
second_title: Aspose.Slides pro C++ – API referenční příručka
description: Ověřuje, zda je textový obsah elementu platný podle jeho datového typu u elementů s jednoduchým obsahem, a ověřuje, zda je obsah aktuálního elementu kompletní u elementů s komplexním obsahem.
type: docs
weight: 209
url: /cs/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) metoda

Ověřuje, zda je textový obsah elementu platný podle jeho datového typu pro elementy s jednoduchým obsahem, a ověřuje, zda je obsah aktuálního elementu kompletní pro elementy s komplexním obsahem.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Objekt [XmlSchemaInfo](../../xmlschemainfo/), jehož vlastnosti jsou nastaveny při úspěšné validaci elementu. Tento parametr může být **nullptr**. |

### Návratová hodnota

Parsovaná, typovaná textová hodnota elementu, pokud má element jednoduchý obsah.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) metoda

Ověřuje, zda je textový obsah uvedeného elementu platný podle jeho datového typu.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Objekt [XmlSchemaInfo](../../xmlschemainfo/), jehož vlastnosti jsou nastaveny při úspěšné validaci textového obsahu elementu. Tento parametr může být **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Typovaný textový obsah elementu. |

### Návratová hodnota

Parsovaný, typovaný jednoduchý obsah elementu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [XmlSchemaInfo](../../xmlschemainfo/)
* Třída [XmlSchemaValidator](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)