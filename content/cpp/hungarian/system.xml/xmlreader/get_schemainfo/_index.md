---
title: get_SchemaInfo()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaadja a sémainformációt, amelyet a séma validálás eredményeként a jelenlegi csomóponthoz rendeltek.
type: docs
weight: 196
url: /hu/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() metódus


Visszaadja a séma információt, amelyet a séma validálás eredményeként a jelenlegi csomóponthoz rendeltek.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### Visszatérési érték

Egy IXmlSchemaInfo objektum, amely a jelenlegi csomóponthoz tartozó séma információt tartalmaz. [Schema](../../../system.xml.schema/) információ beállítható elemekre, attribútumokra vagy nem null [XmlReader::get_ValueType](../get_valuetype/) értékkel rendelkező szövegcsomópontokra. Ha a jelenlegi csomópont nem a fenti csomóponttípusok egyike, vagy ha a [XmlReader](../) példány nem jelent séma információt, ez a metódus **nullptr**-t ad vissza. Ha ezt a metódust egy [XmlTextReader](../../xmltextreader/) vagy egy [XmlValidatingReader](../../xmlvalidatingreader/) objektumból hívják, ez a metódus mindig **nullptr**-t ad vissza. Ezek a [XmlReader](../) implementációk nem teszik elérhetővé a séma információt a get_SchemaInfo metóduson keresztül.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)