---
title: get_NameTable()
second_title: Aspose.Slides for C++ Referência da API
description: Retorna o XmlNameTable usado para comparações de strings atomizadas.
type: docs
weight: 1
url: /pt/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() método

Retorna o [XmlNameTable](../../xmlnametable/) usado para comparações de strings atomizadas.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### Valor de retorno

O [XmlNameTable](../../xmlnametable/) que armazena todas as strings atomizadas usadas por todas as instâncias de [XmlReader](../../xmlreader/) criadas usando este objeto [XmlReaderSettings](../). O padrão é **nullptr**. A instância [XmlReader](../../xmlreader/) criada usará um novo [NameTable](../../nametable/) vazio se este valor for **nullptr**.

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNameTable](../../xmlnametable/)
* Classe [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)