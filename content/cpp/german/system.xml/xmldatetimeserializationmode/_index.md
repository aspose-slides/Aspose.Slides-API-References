---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie der Zeitwert bei der Konvertierung zwischen Zeichenfolge und DateTime behandelt wird.
type: docs
weight: 781
url: /de/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

Gibt an, wie der Zeitwert bei der Konvertierung zwischen Zeichenfolge und [DateTime](../../system/datetime/) behandelt wird.

```cpp
enum class XmlDateTimeSerializationMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Local | 0 | Als lokale Zeit behandeln. Wenn das [DateTime](../../system/datetime/)-Objekt eine koordinierte Weltzeit (UTC) darstellt, wird es in die lokale Zeit umgewandelt. |
| Utc | 1 | Als UTC behandeln. Wenn das [DateTime](../../system/datetime/)-Objekt eine lokale Zeit darstellt, wird es in eine UTC umgewandelt. |
| Unspecified | 2 | Als lokale Zeit behandeln, wenn ein [DateTime](../../system/datetime/) in eine Zeichenfolge konvertiert wird. Wenn eine Zeichenfolge in [DateTime](../../system/datetime/) konvertiert wird, in eine lokale Zeit umwandeln, falls eine Zeitzone angegeben ist. |
| RoundtripKind | 3 | Zeitinformationen sollten bei der Konvertierung erhalten bleiben. |

## Siehe auch

* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)