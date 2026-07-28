---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides C++ API Referencia
description: Megadja, hogyan kell kezelni az időértéket a karakterlánc és a DateTime közti átalakítás során.
type: docs
weight: 781
url: /hu/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

Megadja, hogyan kell kezelni az időértéket a karakterlánc és a [DateTime](../../system/datetime/) közti átalakítás során.

```cpp
enum class XmlDateTimeSerializationMode
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Local | 0 | Helyi időként kezelni. Ha a [DateTime](../../system/datetime/) objektum a Koordinált Univerzális Időt (UTC) képviseli, akkor helyi időre konvertálódik. |
| Utc | 1 | UTC-ként kezelni. Ha a [DateTime](../../system/datetime/) objektum helyi időt képvisel, akkor UTC-re konvertálódik. |
| Unspecified | 2 | Helyi időként kezelni, ha a [DateTime](../../system/datetime/) karakterláncra konvertálódik. Ha egy karakterláncot [DateTime](../../system/datetime/)-ra konvertálnak, helyi időre konvertálni, ha időzóna van megadva. |
| RoundtripKind | 3 | Az időzóna-információt meg kell őrizni az átalakítás során. |

## Lásd még

* Névtér [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)