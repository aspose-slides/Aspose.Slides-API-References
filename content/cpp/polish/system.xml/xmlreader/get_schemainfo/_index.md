---
title: get_SchemaInfo()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca informacje o schemacie, które zostały przypisane do bieżącego węzła w wyniku walidacji schematu.
type: docs
weight: 196
url: /pl/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() metoda

Zwraca informacje o schemacie, które zostały przypisane do bieżącego węzła w wyniku walidacji schematu.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### Wartość zwracana

Obiekt IXmlSchemaInfo zawierający informacje o schemacie dla bieżącego węzła. [Schema](../../../system.xml.schema/) informacje mogą być ustawiane na elementach, atrybutach lub na węzłach tekstowych z niepustą wartością [XmlReader::get_ValueType](../get_valuetype/). Jeśli bieżący węzeł nie jest jednym z powyższych typów węzłów lub jeśli instancja [XmlReader](../) nie raportuje informacji o schemacie, ta metoda zwraca **nullptr**. Jeśli metoda ta jest wywoływana z obiektu [XmlTextReader](../../xmltextreader/) lub [XmlValidatingReader](../../xmlvalidatingreader/), metoda zawsze zwraca **nullptr**. Te implementacje [XmlReader](../) nie udostępniają informacji o schemacie poprzez metodę get_SchemaInfo.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Klasa [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)