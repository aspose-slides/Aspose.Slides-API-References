---
title: Compile()
second_title: Aspose.Slides for C++ API referencia
description: Lefordítja az XML SchemaObject Model (SOM) modellt sémainformációkká az érvényesítéshez. A programozottan létrehozott SOM szintaktikai és szemantikai struktúrájának ellenőrzésére használják. A szemantikai validációs ellenőrzés a fordítás során történik.
type: docs
weight: 352
url: /hu/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) metódus


Lefordítja az XML [Schema](../../)[Object](../../../system/object/) Modellt (SOM) sémainformációkká az érvényesítéshez. A programozottan előállított SOM szintaktikai és szemantikai struktúrájának ellenőrzésére szolgál. A szemantikai érvényesítési ellenőrzés a fordítás során történik.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Az azonosító eseménykezelő, amely információkat kap az XML [Schema](../../) validációs hibáiról. |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) metódus


Lefordítja az XML [Schema](../../)[Object](../../../system/object/) Modellt (SOM) sémainformációkká az érvényesítéshez. A programozottan előállított SOM szintaktikai és szemantikai struktúrájának ellenőrzésére szolgál. A szemantikai érvényesítési ellenőrzés a fordítás során történik.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Az azonosító eseménykezelő, amely információkat kap az XML [Schema](../../) validációs hibáiról. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/), amelyet a **include** és **import** elemekben hivatkozott névtér feloldására használnak. |

## Lásd még

* Típusdefiníció [ValidationEventHandler](../../validationeventhandler/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchema](../)
* Osztály [XmlResolver](../../../system.xml/xmlresolver/)
* Névterület [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)