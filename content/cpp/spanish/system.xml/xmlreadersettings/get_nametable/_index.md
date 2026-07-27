---
title: get_NameTable()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el XmlNameTable usado para comparaciones de cadenas atomizadas.
type: docs
weight: 1
url: /es/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() método

Devuelve el [XmlNameTable](../../xmlnametable/) usado para comparaciones de cadenas atomizadas.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### Valor devuelto

El [XmlNameTable](../../xmlnametable/) que almacena todas las cadenas atomizadas usadas por todas las instancias [XmlReader](../../xmlreader/) creadas usando este objeto [XmlReaderSettings](../). El valor predeterminado es **nullptr**. La instancia [XmlReader](../../xmlreader/) creada utilizará un nuevo [NameTable](../../nametable/) vacío si este valor es **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNameTable](../../xmlnametable/)
* Clase [XmlReaderSettings](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)