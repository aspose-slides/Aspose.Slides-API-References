---
title: get_BaseURI()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar nodens bas Uniform Resource Identifier (URI).
type: docs
weight: 183
url: /sv/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() metod


Returnerar bas Uniform Resource Identifier (URI) för noden.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### Returvärde

Platsen varifrån noden lästes in eller [String::Empty](../../../system/string/empty/) om noden saknar bas-URI. [Attribute](../../../system/attribute/)-noder har samma bas-URI som deras ägarelement. Om ett attributnod saknar ett ägarelement, get_BaseURI returnerar [String::Empty](../../../system/string/empty/).

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlAttribute](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)