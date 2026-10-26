---
title: get_BaseURI()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaadja a csomópont alap Uniform Resource Identifier (URI) értékét.
type: docs
weight: 183
url: /hu/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() metódus


Visszaadja a csomópont bázis Uniform Resource Identifier (URI) értékét.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### Visszatérési érték

A hely, ahonnan a csomópont betöltődött, vagy [String::Empty](../../../system/string/empty/), ha a csomópontnak nincs bázis URI-ja. [Attribute](../../../system/attribute/) csomópontok ugyanazzal a bázis URI-val rendelkeznek, mint a tulajdonos elemük. Ha egy attribútumcsomópontnak nincs tulajdonos eleme, a get_BaseURI [String::Empty](../../../system/string/empty/).

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlAttribute](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)