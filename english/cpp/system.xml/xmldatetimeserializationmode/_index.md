---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides for C++ API Reference
description: Specifies how to treat the time value when converting between string and DateTime.
type: docs
weight: 781
url: /cpp/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum


Specifies how to treat the time value when converting between string and [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Local | 0 | Treat as local time. If the [DateTime](../../system/datetime/) object represents a Coordinated Universal Time (UTC), it is converted to the local time. |
| Utc | 1 | Treat as a UTC. If the [DateTime](../../system/datetime/) object represents a local time, it is converted to a UTC. |
| Unspecified | 2 | Treat as a local time if a [DateTime](../../system/datetime/) is being converted to a string. If a string is being converted to [DateTime](../../system/datetime/), convert to a local time if a time zone is specified. |
| RoundtripKind | 3 | Time zone information should be preserved when converting. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)
