---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, jak zacházet s časovou hodnotou při převodu mezi řetězcem a DateTime.
type: docs
weight: 781
url: /cs/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode výčet

Určuje, jak zacházet s časovou hodnotou při převodu mezi řetězcem a [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Local | 0 | Zacházet jako s místním časem. Pokud objekt [DateTime](../../system/datetime/) představuje koordinovaný světový čas (UTC), je převeden na místní čas. |
| Utc | 1 | Zacházet jako s UTC. Pokud objekt [DateTime](../../system/datetime/) představuje místní čas, je převeden na UTC. |
| Unspecified | 2 | Zacházet jako s místním časem, pokud se [DateTime](../../system/datetime/) převádí na řetězec. Pokud se řetězec převádí na [DateTime](../../system/datetime/), převést na místní čas, pokud je uvedeno časové pásmo. |
| RoundtripKind | 3 | Informace o časovém pásmu by měly být při převodu zachovány. |

## Viz také

* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)