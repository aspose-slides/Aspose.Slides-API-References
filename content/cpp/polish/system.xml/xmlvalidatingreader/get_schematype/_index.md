---
title: get_SchemaType()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca obiekt typu schematu.
type: docs
weight: 287
url: /pl/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() metoda


Zwraca obiekt typu schematu.

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```


### Wartość zwracana

XmlSchemaDatatype, XmlSchemaSimpleType lub XmlSchemaComplexType w zależności od tego, czy wartość węzła jest wbudowanym XML [Schema](../../../system.xml.schema/) definition language (XSD) type lub typem prostym zdefiniowanym przez użytkownika simpleType lub typem złożonym complexType; **nullptr** jeśli bieżący węzeł nie ma typu schematu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [XmlValidatingReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)