---
title: Initialize()
second_title: Aspose.Slides C++ API referencia
description: Inicializálja az XmlSchemaValidator objektum állapotát.
type: docs
weight: 118
url: /hu/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() metódus


Inicializálja a [XmlSchemaValidator](../) objektum állapotát.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```


## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) metódus


Inicializálja a [XmlSchemaValidator](../) objektum állapotát a részleges validáláshoz megadott [XmlSchemaObject](../../xmlschemaobject/) használatával.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | [XmlSchemaElement](../../xmlschemaelement/), [XmlSchemaAttribute](../../xmlschemaattribute/) vagy [XmlSchemaType](../../xmlschematype/) objektum, amely a [XmlSchemaValidator](../) objektum validálási környezetét inicializálja részleges validáláshoz. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchemaValidator](../)
* Osztály [XmlSchemaObject](../../xmlschemaobject/)
* Névterület [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)