---
title: WriteState
second_title: Aspose.Slides C++ API referencia
description: Meghatározza az XmlWriter állapotát.
type: docs
weight: 755
url: /hu/system.xml/writestate/
---
## WriteState enum


Meghatározza a [XmlWriter](../xmlwriter/) állapotát.

```cpp
enum class WriteState
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Start | 0 | Azt jelzi, hogy az XmlWriter::Write metódust még nem hívták meg. |
| Prolog | 1 | Azt jelzi, hogy a prolog írás alatt van. |
| Element | 2 | Azt jelzi, hogy egy elem kezdőcímke írásra kerül. |
| Attribute | 3 | Azt jelzi, hogy egy attribútum értéke írásra kerül. |
| Content | 4 | Azt jelzi, hogy egy elem tartalma írásra kerül. |
| Closed | 5 | Azt jelzi, hogy a [XmlWriter::Close](../xmlwriter/close/) metódust meghívták. |
| Error | 6 | Kivétel lett dobva, amely a [XmlWriter](../xmlwriter/)-t érvénytelen állapotba helyezte. Meghívhatja a [XmlWriter::Close](../xmlwriter/close/) metódust, hogy a [XmlWriter](../xmlwriter/)-t a [WriteState::Closed](./) állapotba tegye. Bármely más [XmlWriter](../xmlwriter/) metódushívás InvalidOperationException-t eredményez. |

## Lásd még

* Névtere [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)