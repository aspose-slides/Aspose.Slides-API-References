---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar XmlSchema som är associerad med den angivna namnrymds-URI:n.
type: docs
weight: 53
url: /sv/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) metod

Returnerar den [XmlSchema](../../xmlschema/) som är associerad med den angivna namnrymds-URI:n.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Den namnrymds-URI som är associerad med schemat du vill returnera. Detta är vanligtvis **targetNamespace** för schemat. |

### Returvärde

Den [XmlSchema](../../xmlschema/) som är associerad med namnrymds-URI:n; **nullptr** om det inte finns något laddat schema associerat med den angivna namnrymden eller om namnrymden är associerad med ett XDR-schema.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlSchema](../../xmlschema/)
* Klass [String](../../../system/string/)
* Klass [XmlSchemaCollection](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)