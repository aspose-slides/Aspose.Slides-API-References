---
title: idx_get()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan XmlSchema yang terkait dengan namespace URI yang diberikan.
type: docs
weight: 53
url: /id/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) metode


Mengembalikan [XmlSchema](../../xmlschema/) yang terkait dengan namespace URI yang diberikan.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI namespace yang terkait dengan skema yang ingin Anda kembalikan. Ini biasanya akan menjadi **targetNamespace** dari skema. |

### Nilai Kembalian

[XmlSchema](../../xmlschema/) yang terkait dengan namespace URI; **nullptr** jika tidak ada skema yang dimuat yang terkait dengan namespace yang diberikan atau jika namespace tersebut terkait dengan skema XDR.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlSchema](../../xmlschema/)
* Kelas [String](../../../system/string/)
* Kelas [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)