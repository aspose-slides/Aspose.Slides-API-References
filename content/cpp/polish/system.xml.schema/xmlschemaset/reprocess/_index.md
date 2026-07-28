---
title: Reprocess()
second_title: Aspose.Slides dla C++ referencja API
description: Ponownie przetwarza schemat języka definicji XML Schema (XSD), który już istnieje w XmlSchemaSet.
type: docs
weight: 222
url: /pl/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) metoda

Ponownie przetwarza schemat języka definicji XML [Schema](../../) (XSD), który już istnieje w [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Schemat do ponownego przetworzenia. |

### Wartość zwracana

Obiekt [XmlSchema](../../xmlschema/), jeśli schemat jest prawidłowy. Jeśli schemat nie jest prawidłowy i określono ValidationEventHandler, zwracane jest **nullptr** i podnoszone jest odpowiednie zdarzenie walidacji. W przeciwnym razie zgłaszany jest XmlSchemaException.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlSchema](../../xmlschema/)
* Klasa [XmlSchemaSet](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)