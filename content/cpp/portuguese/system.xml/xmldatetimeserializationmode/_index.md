---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides para C++ Referência da API
description: Especifica como tratar o valor de tempo ao converter entre string e DateTime.
type: docs
weight: 781
url: /pt/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

Especifica como tratar o valor de tempo ao converter entre string e [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Local | 0 | Tratar como hora local. Se o objeto [DateTime](../../system/datetime/) representa um Tempo Universal Coordenado (UTC), ele é convertido para a hora local. |
| Utc | 1 | Tratar como UTC. Se o objeto [DateTime](../../system/datetime/) representa uma hora local, ele é convertido para UTC. |
| Unspecified | 2 | Tratar como hora local se um [DateTime](../../system/datetime/) está sendo convertido para string. Se uma string está sendo convertida para [DateTime](../../system/datetime/), converter para hora local se um fuso horário for especificado. |
| RoundtripKind | 3 | A informação de fuso horário deve ser preservada ao converter. |

## Veja Também

* Namespace [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)