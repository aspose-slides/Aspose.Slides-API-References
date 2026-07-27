---
title: idx_get()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o XmlSchema associado ao namespace URI fornecido.
type: docs
weight: 53
url: /pt/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) método

Retorna o [XmlSchema](../../xmlschema/) associado ao namespace URI fornecido.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | O namespace URI associado ao esquema que você deseja retornar. Normalmente será o **targetNamespace** do esquema. |

### Valor de retorno

O [XmlSchema](../../xmlschema/) associado ao namespace URI; **nullptr** se não houver esquema carregado associado ao namespace fornecido ou se o namespace estiver associado a um esquema XDR.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)