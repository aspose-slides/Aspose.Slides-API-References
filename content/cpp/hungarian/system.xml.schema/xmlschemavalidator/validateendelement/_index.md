---
title: ValidateEndElement()
second_title: Aspose.Slides for C++ API-referencia
description: Ellenőrizze, hogy az elem szövegtartalma érvényes-e az adat típusa szerint az egyszerű tartalmú elemek esetén, és ellenőrizze, hogy a jelenlegi elem tartalma teljes-e a komplex tartalmú elemeknél.
type: docs
weight: 209
url: /hu/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) metódus

Ellenőrizze, hogy az elem szövegtartalma érvényes-e az adat típusa szerint az egyszerű tartalmú elemek esetén, és ellenőrizze, hogy az aktuális elem tartalma teljes-e a komplex tartalmú elemeknél.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Egy [XmlSchemaInfo](../../xmlschemainfo/) objektum, amelynek tulajdonságai az elem sikeres érvényesítésekor kerülnek beállításra. Ez a paraméter lehet **nullptr**. |

### Visszatérési érték

A feldolgozott, típusos szöveges érték az elemből, ha az elemnek egyszerű tartalma van.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) metódus

Ellenőrizze, hogy a megadott elem szövegtartalma érvényes-e az adat típusa szerint.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Egy [XmlSchemaInfo](../../xmlschemainfo/) objektum, amelynek tulajdonságai az elem szövegtartalmának sikeres validálása után kerülnek beállításra. Ez a paraméter lehet **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Az elem típusos szövegtartalma. |

### Visszatérési érték

Az elem feldolgozott, típusos egyszerű tartalma.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)