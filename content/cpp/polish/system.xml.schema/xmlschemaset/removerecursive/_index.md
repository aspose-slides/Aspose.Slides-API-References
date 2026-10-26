---
title: RemoveRecursive()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Usuwa określony schemat języka definicji XML (XSD) oraz wszystkie schematy, które on importuje z XmlSchemaSet.
type: docs
weight: 183
url: /pl/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) metoda

Usuwa określony schemat języka definicji XML [Schema](../../) (XSD) oraz wszystkie schematy, które on importuje z [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Obiekt [XmlSchema](../../xmlschema/) do usunięcia z [XmlSchemaSet](../). |

### Wartość zwracana

**true** jeśli obiekt [XmlSchema](../../xmlschema/) i wszystkie jego importy zostały pomyślnie usunięte; w przeciwnym razie **false**.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlSchema](../../xmlschema/)
* Klasa [XmlSchemaSet](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)